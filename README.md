# Sai Manaswini Kotla — Portfolio & Representation

A high-performance, modern, dark-themed portfolio web application built for fashion, editorial, and commercial model **Sai Manaswini Kotla**.

## 🌟 Features

* **Modern Dark UI:** High-contrast, luxury aesthetic designed using Tailwind CSS v4.
* **Responsive Layout:** Optimized for all screen sizes from mobile devices to desktop displays.
* **Interactive Lightbox:** Full-screen gallery viewer powered by Lightgallery.js with zoom and thumbnail navigation.
* **Contact Integration:** Functional inquiry form powered by Formspree.
* **Automated CI/CD:** GitHub Actions workflow configured for seamless build and deployment to GitHub Pages.

---

## 🛠️ Tech Stack

* **Framework/Bundler:** [Vite](https://vitejs.dev/)
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) (`@tailwindcss/vite`)
* **Gallery:** [Lightgallery.js](https://www.lightgalleryjs.com/)
* **Typography & Icons:** Google Fonts (Playfair Display & Plus Jakarta Sans), FontAwesome 6
* **Form Handling:** [Formspree](https://formspree.io/)
* **Hosting:** GitHub Pages via GitHub Actions

---

## 🚀 Local Development Setup

Follow these steps to run and test the project on your local machine before pushing changes to GitHub.

### 1. Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (v18 or higher) and **npm** installed on your system. You can verify installation by running:

```bash
node -v
npm -v

2. Clone the Repository
Bash
git clone [https://github.com/kalelynooranilkumar/model-portfolio.git](https://github.com/kalelynooranilkumar/model-portfolio.git)
cd model-portfolio

3. Install Dependencies
Install all required package dependencies (Vite, Tailwind CSS, Lightgallery, etc.):

Bash
npm install

4. Start Development Server
Run the local development server with hot-reload:

Bash
npm run dev
After running the command, open your browser and navigate to:
http://localhost:5173

📦 Building & Production Deployment
Local Production Build Test
To test the production bundle locally:

Bash
# Build the application output into the dist/ directory
npm run build

# Preview the local production build
npm run preview
Automated GitHub Pages Deployment
Pushing changes to the main branch automatically triggers the .github/workflows/deploy.yml workflow, which builds and publishes the live site to GitHub Pages:

https://kalelynooranilkumar.github.io/model-portfolio/

Deployment Commands:
PowerShell
git add .
git commit -m "Update portfolio content and styling"
git push origin main