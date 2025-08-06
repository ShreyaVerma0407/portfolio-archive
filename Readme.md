# Shreya Verma | Portfolio Website

This is my personal portfolio website showcasing my skills, projects, education, and contact information. Built with modern web technologies, it features a clean, responsive design with interactive elements and a downloadable resume.

---

## 🎯 Project Features

- **Clean, modern, and responsive design** — utilizes glassmorphism effect on header and footer.
- **Sticky navigation header** with smooth scroll to different sections.
- **Sidebar** with profile picture, availability toggle, social links, and resume download button.
- **Sections include:** Hero/Intro, Experience, Projects, Education, Tech Stacks, Contact Form.
- **Interactive contact form** integrated with EmailJS for messaging.
- **Scroll reveal animations** for enhanced user experience.
- **Projects link to GitHub repositories.**
- **Accessibility support** with ARIA attributes and keyboard navigation.

---

## 🚀 Technologies Used

- HTML5 & CSS3 (Flexbox, Grid, variables)
- JavaScript (ES6+)
- Font Awesome (Icons)
- Google Fonts (Inter, Great Vibes)
- EmailJS (for contact form)
- Responsive design with media queries
- UI/UX design inspired by Figma and Canva

---

## 📁 Project Structure

```
README.md                   # This file
cv.html                     # Main portfolio HTML file
styles.css                  # Main stylesheet
image.png                   # Project image 1
image1.png                  # Project image 2
image2.png                  # Project image 3
image3.png                  # Project image 4
profile.png                 # Profile picture image
Shreya_Verma_CV.pdf         # Downloadable resume PDF
```

---

## 📄 How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/your-portfolio-repo.git
    ```

2. **Open `cv.html` in your web browser** to view the portfolio.

3. **Update personal information, project details, and links** in `cv.html` as needed.

4. **Ensure all referenced images** (`image.png`, `image1.png`, etc.) are in the same folder as `cv.html`.

5. The **"Download Resume"** button links to `Shreya_Verma_CV.pdf` for easy downloading.

6. To enable contact form functionality, **configure [EmailJS](https://www.emailjs.com/)** with your own service/template keys inside the HTML file.

---

## 📩 Contact Form Configuration

This website uses EmailJS to send messages without requiring a backend:

1. **Replace the Public API key** in the script section of `cv.html`:

    ```js
    emailjs.init("YOUR_PUBLIC_API_KEY");
    ```

2. **Replace Service and Template IDs** in the form submission code:

    ```js
    emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", templateParams)
    ```

3. See the [EmailJS documentation](https://www.emailjs.com/docs/) for setup instructions.

---

## ✨ Credits

- UI/UX inspired by Figma and Canva
- Icons from [Font Awesome](https://fontawesome.com/)
- Fonts: [Inter](https://fonts.google.com/specimen/Inter), [Great Vibes](https://fonts.google.com/specimen/Great+Vibes)
- Contact form powered by [EmailJS](https://www.emailjs.com/)

---

## 📫 Contact

Feel free to reach out via the contact form on the website or connect with me on [LinkedIn](https://linkedin.com/in/shreyaverma0407) or [GitHub](https://github.com/ShreyaVerma0407).

---

*Made with ❤️ by Shreya Verma*