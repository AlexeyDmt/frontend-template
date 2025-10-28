# 🚀 Frontend Template

A minimal template for frontend projects using HTML, SCSS, and JS.

## 🧩 Features
- Dev server via **lite-server**
- Automatic **SCSS → CSS** compilation
- Build and deploy to **GitHub Pages**
- Minimal structure, ready for expansion

---

## ⚙️ Scripts

| Command          | Description                         |
| ---------------- | ----------------------------------- |
| `npm run dev`    | Start the dev server and watch SCSS |
| `npm run build`  | Build the project into `dist`       |
| `npm run deploy` | Deploy to GitHub Pages              |

---

## 📁 Project Structure

<pre><code>
src/
├── scss/
│   └── style.scss
├── css/
│   └── style.css   # generated from SCSS
├── js/
│   └── main.js
├── assets/
│   └── img/
└── index.html
</code></pre>


---

## Using as a Template

1. Click **Use this template** on the repository page.

2. Clone your new project to your computer:
   ```bash
   git clone https://github.com/your-username/new-project.git
   cd new-project

3. Change into the project directory:
   ```bash
   cd new-project

4. If the repository is not yet initialized, run:
   ```bash
   git init

5. Install dependencies:
   ```bash
   npm install

6. Start the dev server:
   ```bash
   npm run dev