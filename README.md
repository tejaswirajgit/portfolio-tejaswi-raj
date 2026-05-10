# Tejaswi Raj — Portfolio

[![Live Site](https://img.shields.io/badge/Live-tejaswirajgit.github.io-64ffda?style=flat-square)](https://tejaswirajgit.github.io/portfolio-tejaswi-raj/)
[![GitHub](https://img.shields.io/badge/GitHub-tejaswirajgit-181717?style=flat-square&logo=github)](https://github.com/tejaswirajgit)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tejaswi%20Raj-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/tejaswi-raj-/)

Computer Science Engineer (2025 graduate) focused on building AI-driven and scalable web applications. This repository hosts the source for my personal portfolio site — experience, ML/DL project notebooks, publications, and certifications.

**Live site:** <https://tejaswirajgit.github.io/portfolio-tejaswi-raj/>

## About me

🛠️ **Currently working on** — AI-powered applications, backend APIs, and production-ready web platforms using modern tech stacks.

🤝 **Looking to collaborate on** — AI projects, full-stack applications, SaaS products, and open-source tools that solve real-world problems.

🆘 **Looking for help with** — system design decisions, scaling AI applications, and best practices for production deployment.

🌱 **Currently learning** — advanced backend architecture, cloud deployment, AI model integration, and performance optimization.

💬 **Ask me about** — Machine Learning, API development, backend systems, AI integration, and full-stack project workflows.

⚡ **Fun fact** — I enjoy turning complex problems into clean, working systems.

## Education

**B.E. in Computer Science Engineering** — Chandigarh University, Mohali, Punjab
Graduated 2025 · CGPA: 7.56

## Featured projects

ML projects rendered directly from their Jupyter notebooks, with deployed live demos where applicable.

| Project | Notebook | Live demo |
| --- | --- | --- |
| Plant Leaf Disease Detection — CNN classifier | [View notebook](notebooks/Plant%20Leaf%20Disease%20Detection.html) | [Hugging Face Space ↗](https://huggingface.co/spaces/workface/plant-disease-detection) |
| ML-Based Cardiovascular Disease Prediction & Prevention Framework | [View notebook](notebooks/ML-Based%20Cardiovascular%20Disease%20Prediction%20%26%20Prevention%20Framework.html) | [Streamlit app ↗](https://cardiovascular-disease-risk-predictor.streamlit.app/) |

## Tech stack

- **Frontend** — HTML5, CSS3 (custom design system, Inter typography, dark navy palette with `#64ffda` accent), vanilla JavaScript: `IntersectionObserver`-based reveal animations, hero typing effect, project-card 3D tilt, smooth scroll, cursor glow.
- **Notebooks** — Python, Jupyter, scikit-learn, TensorFlow / Keras, rendered to static HTML via `nbconvert`.
- **Hosting** — GitHub Pages, served from `main` branch root.

No build step, no framework runtime, no bundler — open `index.html` and it runs.

## Run locally

```bash
git clone https://github.com/tejaswirajgit/portfolio-tejaswi-raj.git
cd portfolio-tejaswi-raj
python -m http.server 8000
# then open http://localhost:8000
```

Regenerate the rendered notebook HTML after editing any `.ipynb`:

```bash
python convert_notebooks.py
```

## Repository structure

```text
.
├── index.html              # Single-page site (sections: hero, about, experience,
│                           #   projects, publications, certifications, education, contact)
├── styles.css              # Visual system
├── script.js               # All interactivity in one file
├── convert_notebooks.py    # Converts .ipynb -> notebooks/*.html
├── notebooks/              # Rendered project notebooks (HTML)
├── Coursera Certificate/   # Coursera completion PDFs (linked from the certifications grid)
└── DRDO Certificate.pdf    # DRDO experience certificate (linked from the timeline)
```

## Contact

- Email — [tejaswirajmgr@gmail.com](mailto:tejaswirajmgr@gmail.com)
- LinkedIn — [tejaswi-raj-](https://www.linkedin.com/in/tejaswi-raj-/)
- GitHub — [@tejaswirajgit](https://github.com/tejaswirajgit)
