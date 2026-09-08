Lediea — E-Learning Platform

An open-source, multi-page e-learning website built with HTML, CSS, and JavaScript — bringing together courses, resources, events, blogs, and a community space for learners in one place.


## 📌 About

Lediea is a static, front-end e-learning platform covering both in-syllabus and out-of-syllabus learning needs: course listings, subject-wise resources, sample papers, quizzes, events, a blog, and a community/counselling section — all wrapped in a responsive, animated UI.

## ✨ Features

- **Home page** with hero section, feature highlights, and animated UI elements
- **Courses** — browsable course catalog (`Course/Courses.html`)
- **Subjects** — dedicated pages per subject (Data Science, IT, Marketing, Finance, Cyber Security, Maths, Arts & Humanity, and more) plus competitive-exam pages (JEE, NEET, GATE)
- **Quizzes** — interactive quiz page (`subjects/quiz.html`) for self-assessment
- **Resource Page** — curated learning resources and materials
- **Blog** — articles and posts (`Blog/blog.html`)
- **Events** — upcoming events and workshops (`Events/events.html`)
- **Community** — space to connect with other learners (`community/community.html`)
- **Counselling** — guidance/counselling section
- **Teach on Lediea** — page for prospective instructors to get started
- **Login / Signup** — authentication pages (`log in/Login.html`)
- **Contact & About** pages, including a team page
- Fully responsive layout with carousels, preloaders, and scroll animations

## 🛠️ Tech Stack

![HTML](https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

**Libraries/plugins used:** Slick Carousel, Owl Carousel, AOS (Animate on Scroll), Font Awesome, and custom preloader/animation scripts.

This is a purely front-end project — no backend framework or database is included; login/signup pages are static markup and scripts (`log in/*.js`) ready to be wired up to a backend of your choice.

## 📂 Project Structure

```
Lediea-E-learning-Platfrom/
├── index.html              # Home page
├── Courses.html             # Top-level courses page
├── style.css / navbar.css   # Global and navbar styles
├── css/                     # Shared stylesheets (main, utility, responsive, courses)
├── js/                      # Shared scripts (preloader, animations, course scripts)
├── img/                     # Site-wide images
├── Course/                  # Course listing page + assets, scripts, subjects, sample papers
├── subjects/                # Individual subject pages + quiz page
├── Blog/                    # Blog pages and assets
├── Events/                  # Events page and assets
├── Resource_Page/           # Learning resources page
├── community/                # Community page
├── counselling/               # Counselling page
├── contact/                  # Contact page
├── about/                     # About / team page
├── feature-pg/                # Features page
├── teach-on-bigb/              # "Teach on Lediea" page for instructors
├── log in/                    # Login / signup pages and scripts
├── slick-1.8.1/                # Slick Carousel library
└── .github/ISSUE_TEMPLATE/      # Issue templates for contributors
```

## 🚀 Getting Started

Since this is a static site, no build step or server-side setup is required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/pankaj-patell/Lediea.git
   cd Lediea
   ```
2. **Open it in a browser**
   - Simply open `index.html` in your browser, **or**
   - Serve it locally for a smoother experience with relative paths (recommended), e.g. using the VS Code "Live Server" extension, or:
     ```bash
     npx serve .
     ```
     then visit the printed local URL.

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch: `git checkout -b <feature-branch>`
3. Make your changes and commit: `git commit -m "<message>"`
4. Push to your fork: `git push origin <feature-branch>`
5. Open a pull request describing your changes.

Please check the `.github/ISSUE_TEMPLATE/` folder for bug report, feature request, and doc issue templates when filing issues.

## 📄 License

No license file is currently included in this project. Add a `LICENSE` file (e.g. MIT) if you intend to open-source it under a specific license.

## 📬 Contact

For questions or suggestions, please open an issue on this repository.
