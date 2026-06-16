# 📄 Sahil Jain — Software Development Engineer (SDE)

Welcome to the repository for my professional resume. This repository serves as the single source of truth for my resume and hosts an automated deployment pipeline to compile and serve it online.

## 🔗 Quick Links

- **🌐 Portfolio:** [imsahiljain.in](https://imsahiljain.in)
- **💼 LinkedIn:** [linkedin.com/in/imsahiljain](https://www.linkedin.com/in/imsahiljain/)
- **💻 GitHub:** [github.com/im-sahiljain](https://github.com/im-sahiljain)
- **📄 Live Interactive Resume:** [resume.imsahiljain.in](https://resume.imsahiljain.in/)

---

## 📞 Contact Details

- **Email:** [mr.sahiljain14@gmail.com](mailto:mr.sahiljain14@gmail.com)

---

## 🛠️ Repository Features & Architecture

This repository is designed to automate the process of maintaining, compiling, and sharing my resume:

1. **LaTeX Source (`resume.tex`):** My resume is written in LaTeX for precise formatting and a clean, professional aesthetic.
2. **Automated LaTeX Compilation (GitHub Actions):** On every push/merge to the `main` branch, a GitHub Actions workflow compiles the `.tex` file into a production-ready PDF (`resume.pdf`).
3. **GitHub Pages Deployment:** The compiled PDF, along with the interactive web wrapper (`index.html`), is deployed automatically to the `gh-pages` branch and served live at [resume.imsahiljain.in](https://resume.imsahiljain.in/).
4. **Analytics & Source Tracking:** Built-in support for Google Analytics to track resume views and attribute traffic to specific sources.

---

## 💻 Tech Stack & Skills Featured

- **Languages:** JavaScript (ES6+), TypeScript, HTML5, CSS3, Python
- **Frontend:** React.js, Redux Toolkit, Next.js, Tailwind CSS, Ant Design, Material UI, Recharts
- **Backend:** Node.js, Express.js, Django (REST APIs)
- **Databases:** MongoDB, MySQL
- **Tools & DevOps:** Git, GitHub, Docker, Linux, Vercel, NPM, Figma, Jest

---

## 📊 Analytics & URL Tracking

This resume includes custom tracking capabilities to monitor views and determine which platforms or applications are generating interest.

### Generating Trackable Links

You can use the built-in [link-generator.html](file:///home/sahil/Desktop/Prep/resume/generators/link-generator.html) tool located in the `generators` directory to create custom, trackable URLs for your job applications:

- **For LinkedIn Applications:**
  `https://resume.imsahiljain.in/?source=linkedin&medium=application&campaign=senior_sde`
- **For Recruiter Outreach:**
  `https://resume.imsahiljain.in/?source=email&medium=recruiter&campaign=direct_outreach`

To set up Google Analytics for your own tracking, refer to the [TRACKING_SETUP.md](file:///home/sahil/Desktop/Prep/resume/TRACKING_SETUP.md) guide.

---

## 🚀 How to Run Locally

If you want to edit or compile the resume locally:

1. **Prerequisites:** Ensure you have a LaTeX distribution (like TeX Live or MiKTeX) installed.
2. **Compile LaTeX:**
   ```bash
   pdflatex resume.tex
   ```
3. **Local Web Server (to preview the HTML template):**
   ```bash
   npx serve .
   ```
