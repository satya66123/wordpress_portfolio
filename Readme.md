# Satya Srinath Nekkanti - Portfolio Website

This is a personal portfolio website for **Satya Srinath Nekkanti**, built using **WordPress, PHP, and Bootstrap**. The website showcases projects, skills, certifications, experience, education, and contact information, fully responsive and dynamic.

---

## **Table of Contents**

- [Demo](#demo)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Structure](#project-structure)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [License](#license)  

---

## **Demo**

- Localhost URL: `http://localhost/wordpress`  
- [Live version (optional)](your-live-site-url)

---

## **Features**

- Fully responsive design using **Bootstrap 5**  
- Dynamic pages powered by **WordPress & PHP**  
- Sections included:
  - About Me
  - Skills
  - Projects (CRUD, AI apps, OpenAI-integrated apps, live websites)
  - Certifications
  - Experience
  - Education
  - Contact form
- Custom theme with modular **PHP partials** for each section  
- SEO-friendly and optimized for performance  
- External links to LinkedIn and GitHub integrated  

---

## **Technologies Used**

- **WordPress** - CMS for backend management  
- **PHP** - Custom theme development and dynamic content rendering  
- **Bootstrap 5** - Frontend design and responsiveness  
- **HTML5 & CSS3** - Web markup and styling  
- **JavaScript** - Interactive UI elements  
- **MySQL** - Database management  

---

## **Project Structure**

```

wordpress/
├─ wp-content/
│  ├─ themes/
│  │  └─ my-portfolio/
│  │     ├─ style.css
│  │     ├─ functions.php
│  │     ├─ header.php
│  │     ├─ footer.php
│  │     ├─ index.php
│  │     └─ partials/
│  │        ├─ about.php
│  │        ├─ projects.php
│  │        ├─ skills.php
│  │        ├─ certifications.php
│  │        ├─ experience.php
│  │        ├─ education.php
│  │        └─ contact.php
└─ wp-config.php

```

---

## **Setup & Installation**

1. Install a local server like **XAMPP, WAMP, MAMP, or LocalWP**.  
2. Start **Apache** and **MySQL**.  
3. Create a **database** for WordPress (e.g., `portfolio_db`).  
4. Download and extract **WordPress** into `htdocs/wordpress`.  
5. Open `http://localhost/wordpress` and follow the WordPress installation steps.  
6. Copy the `my-portfolio` theme folder into `wp-content/themes/`.  
7. Activate the theme via **Dashboard → Appearance → Themes**.  
8. Create pages: About, Skills, Projects, Certifications, Experience, Education, Contact.  
9. Assign templates or include partials for each section if required.  

---

## **Usage**

- Edit content via WordPress dashboard.  
- Update projects, skills, certifications, and contact info dynamically.  
- Customize Bootstrap styling via `style.css` or enqueue additional scripts in `functions.php`.  

---

## **License**

This project is for **personal portfolio use**.  
You may modify or use it for educational purposes, but please give proper credit to the author.  

---

**Author:** Satya Srinath Nekkanti  
**Email:** satyasrinath653512@gmail.com  
**LinkedIn:** [linkedin.com/in/satya-srinath-nekkanti](https://www.linkedin.com/in/satya-srinath-nekkanti-08b012a3)  
**GitHub:** [github.com/satya66123](https://github.com/satya66123)
