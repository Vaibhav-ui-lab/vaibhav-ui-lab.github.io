# Vaibhav Jangid - Full Stack Developer Portfolio

This is a modern, single-page developer portfolio designed to be hosted seamlessly on **GitHub Pages**.

---

## 🚀 How to Host on GitHub Pages (Step-by-Step)

### Option 1: Via GitHub Web Interface
1. Create a new repository on GitHub:
   - For a user site, name it: `<your-username>.github.io` (e.g., `vaibhav-jangid.github.io`)
   - Or name it whatever you like (e.g. `portfolio`).
2. Upload `index.html` to the repository root (`main` or `master` branch).
3. In your GitHub repository:
   - Go to **Settings** > **Pages** (under Code and automation in the sidebar).
   - Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   - Select branch: `main` (or `master`) and folder: `/ (root)`.
   - Click **Save**.
4. In 1–2 minutes, your website will be live at:
   - `https://<your-username>.github.io/` or `https://<your-username>.github.io/portfolio/`

---

### Option 2: Via Git Command Line
```bash
# Navigate to the portfolio folder
cd "C:\Users\Vaibhav\.gemini\antigravity\scratch\portfolio"

# Initialize git repository
git init
git add index.html README.md
git commit -m "Initial commit: developer portfolio"

# Set main branch and remote
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git

# Push to GitHub
git push -u origin main
```

---

## 🎨 Features Included
- **Dark / Light Mode Toggle:** Automatically remembers user preference with LocalStorage.
- **Glassmorphic UI & Ambient Glow:** Built with modern CSS gradients, backdrop filters, and responsive cards.
- **Experience Timeline:** Reflects full tenure at TechHaus Software Services (Senior Associate, Associate, Intern).
- **Featured Projects:** eShipper (Logistics Platform), SmartWMS (Warehouse Management System), and Algo Trading Platform.
- **Technical Skills Matrix:** Categorized into Frontend, Backend/Microservices, Databases, and Cloud/DevOps.
- **AWS Certification & IIT Madras Degree:** Highlighted with credentials and verification tags.
- **Zero Dependencies Build:** Uses Google Fonts and FontAwesome CDN; works directly in any browser with no build step required.
