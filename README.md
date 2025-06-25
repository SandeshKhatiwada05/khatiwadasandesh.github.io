# 🌐 Portfolio Website — Sandesh Khatiwada

This is my personal portfolio website built primarily using **PHP, HTML, CSS, JavaScript**, and styled with **Bootstrap**. It showcases my projects, skills, and contact information.

> 🔗 Live at: [khatiwadasandesh.com.np](https://khatiwadasandesh.com.np)

---

## 🚀 Features

- Responsive & clean design
- Projects showcase section
- Smooth scrolling navigation
- Contact form (PHP-based)
- Linked with Instagram & GitHub
- Hosted with custom domain using **Cloudflare + GitHub Pages**

---

## 🛠️ Built With

| Technology | Usage |
|------------|-------|
| **HTML5**  | Structure |
| **CSS3**   | Styling |
| **JavaScript** | Interactivity |
| **PHP**    | Backend form handling |
| **Bootstrap** | Responsive layout |
| **Cloudflare** | DNS and SSL |
| **GitHub Pages** | Static site hosting |

---

## 🌍 Deployment Steps — GitHub Pages + Cloudflare (Custom Domain)

### 1️⃣ GitHub Repository

- Create a repository named: `khatiwadasandesh.github.io`
- Push your website files (index.php, assets, etc.) into the `main` branch.
  
```bash
git init
git remote add origin https://github.com/yourusername/khatiwadasandesh.github.io
git add .
git commit -m "Initial commit"
git push origin main
```

2️⃣ Configure Custom Domain in GitHub
  1. Go to your GitHub repo → Settings → Pages
        Under Custom Domain, enter: khatiwadasandesh.com.np
  2. GitHub auto-creates a CNAME file in your repo.

3️⃣ Setup Cloudflare (DNS + SSL + Redirects)
    1. Go to https://cloudflare.com
    2. Add a new site: khatiwadasandesh.com.np
    3. Update your domain registrar to point nameservers to Cloudflare (e.g., gina.ns.cloudflare.com, etc.)
    4. In Cloudflare DNS settings:
       Add a CNAME record:
       ```bash
        Type: CNAME
        Name: @
        Target: khatiwadasandesh.github.io
        Proxy status: DNS only
       ```
    5. Enable: SSL/TLS → Full or Flexible
