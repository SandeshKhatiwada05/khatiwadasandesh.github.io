# 🌐 Portfolio Website — Sandesh Khatiwada

This is my personal portfolio website built primarily using **PHP, HTML, CSS, JavaScript**, and styled with **Bootstrap**. It showcases my projects, skills, and contact information.

> 🔗 **Live site:** [khatiwadasandesh.com.np](https://khatiwadasandesh.com.np)

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

| Technology      | Purpose               |
|----------------|------------------------|
| **HTML5**       | Structure              |
| **CSS3**        | Styling                |
| **JavaScript**  | Interactivity          |
| **PHP**         | Backend form handling  |
| **Bootstrap**   | Responsive layout      |
| **Cloudflare**  | DNS, SSL, and proxy    |
| **GitHub Pages**| Static site hosting    |

---

## 🌍 Deployment Steps — GitHub Pages + Cloudflare (Custom Domain)

### 🔧 1. GitHub Repository

1. Create a new repo named: `khatiwadasandesh.github.io`
2. Push your website files (like `index.php`, `assets/`, etc.) to the `main` branch:

```bash
git init
git remote add origin https://github.com/SandeshKhatiwada05/sandeshkhatiwada05.github.io
git add .
git commit -m "Initial commit"
git push origin main
```

---

### 🌐 2. Configure Custom Domain on GitHub

1. Go to `Settings > Pages` in your GitHub repository.  
2. Under **Custom domain**, enter:

```
khatiwadasandesh.com.np
```

3. GitHub will automatically create a `CNAME` file in the repository.

---

### ☁️ 3. Setup Cloudflare for DNS + SSL

1. Visit [cloudflare.com](https://cloudflare.com) and sign up/login.  
2. Add your domain: `khatiwadasandesh.com.np`  
3. Update your **domain registrar** to use Cloudflare's nameservers (e.g., `gina.ns.cloudflare.com`, etc.).  
4. In Cloudflare DNS settings, add the following CNAME:

```
Type:     CNAME  
Name:     @  
Target:   khatiwadasandesh.github.io  
Proxy:    DNS Only
```

5. Go to **SSL/TLS > Overview** and select `Full` or `Flexible` SSL.  
6. Your custom domain is now protected with HTTPS and deployed via GitHub.

---

## 📷 Preview
![image](https://github.com/user-attachments/assets/577860cd-f94b-487d-ae98-7b590d3c541b)
![image](https://github.com/user-attachments/assets/577860cd-f94b-487d-ae98-7b590d3c541b)



---

## 📬 Contact

- 📧 Email: [khatiwadasandesh@gmail.com](mailto:khatiwadasandesh@gmail.com)  
- 🔗 Instagram: [@itsme__sandesh](https://instagram.com/itsme__sandesh)  
- 🌐 Website: [khatiwadasandesh.com.np](https://khatiwadasandesh.com.np)

---

## 📝 License

Free for personal and academic use. Attribution appreciated.
