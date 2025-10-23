# Vo Tri Khoi - Personal Portfolio Website Report

This report provides a detailed overview of my personal portfolio website. It is based on the provided project files: `index.html`, `about.html`, `resume.html`, `map.html`, `contact.html`, `style.css`, and `script.js`.

## 1. Features

The website is a static, multi-page personal portfolio with a clean, modern, and responsive design.

* **Responsive Design:** The site is fully responsive and adapts to various screen sizes, from mobile devices to large desktops, using CSS media queries.

* **Multi-Page Navigation:** The site is organized into five distinct HTML pages, with a navigation bar that highlights the currently active page.

* **Collapsible Sidebar:** On smaller screens, the main sidebar (containing contact info and social links) is collapsed by default and can be toggled with a "Show Contacts" button.

* **Dynamic Content Sections:**

  * **About:** Details the author's professional summary, services offered (AI Engineer, Web Development), and links to competitive programming profiles.

  * **Resume:** A timeline-based resume showcasing Education, Certifications, and a comprehensive Skill Set with animated progress bars.

  * **Map:** An embedded Google Maps iframe displaying a specific location.

* **Interactive Contact Form:** The `contact.html` page features a contact form with client-side validation. The "Send Message" button is disabled via JavaScript until all required fields are filled out correctly, preventing empty submissions.

## 2. Site Map

The website is structured with the following pages:

* `/index.html`: **Home Page**

  * The main landing page with a welcome message.

* `/about.html`: **About Me**

  * Contains a personal introduction, a "What I'm doing" section, and links to competitive programming profiles like Codeforces, VNOJ, DMOJ, Leetcode.

* `/resume.html`: **Resume**

  * Displays the author's education history, certifications, and a list of technical skills with percentage bars.

* `/map.html`: **Map**

  * Features an embedded Google Map showing the author's location.

* `/contact.html`: **Contact**

  * Provides a "Send me a message" form for user inquiries.

## 3. How to Run the Project

This is a static website that requires no server or build process.

**Prerequisite:** A modern web browser (e.g., Chrome, Firefox, Safari, Edge).

**Running Locally:**

The HTML files expect the CSS and JavaScript files to be in an `assets` directory. To run the site correctly, you must organize the files as follows:

1. Create a main project folder (e.g., `portfolio`).

2. Place all the `.html` files (`index.html`, `about.html`, etc.) in the root of this folder.

3. Create an `assets` folder inside the `portfolio` folder.

4. Inside `assets`, create a `css` folder and move `style.css` into it.

5. Inside `assets`, create a `js` folder and move `script.js` into it.

6. Create an `assets/images` folder and move all images (`VNOJ.jpg`, `codeforces.jpg`, `dmoj.jpg`, `my-avatar.jpg`, etc.) into it.

The final structure should look like this:


```
portfolio/
├── index.html
├── about.html
├── resume.html
├── map.html
├── contact.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
        ├── codeforces.jpg
        ├── dmoj.jpg
        ├── leetcode.jpg
        ├── VNOJ.jpg
        ├── my-avatar.jpg
        ├── logo.png
        ├── icon-design.svg
        └── icon-dev.svg
```
        

7. Once the files are arranged, simply **double-click the `index.html` file** to open it in your default web browser.

## 4. Credits

* **Author:** Vo Tri Khoi

* **Technology:**

  * HTML5

  * CSS3

  * Vanilla JavaScript

* **External Libraries:**

  * **Fonts:** [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins)

  * **Icons:** [Ionicons](https://ionicons.com/) and [Font Awesome](https://fontawesome.com/)
