# Personal Portfolio - Shweta Pandya

A modern, highly responsive, and interactive personal portfolio website designed to showcase projects, skills, and professional experience. Built with a sleek dark-mode UI and glassmorphism design principles.

## 🌟 Features
- **Clean & Modern UI**: Aesthetic dark mode with vibrant gradient accents and glassmorphism elements.
- **Fully Responsive**: Adapts seamlessly to all screen sizes (desktop, tablet, and mobile), including a custom mobile hamburger menu.
- **Interactive Animations**: Smooth scroll tracking, sticky navigation, and scroll-triggered fade-in animations.
- **Functional Contact Form**: Integrated with Formspree to securely send messages directly to your email without needing a custom backend server.

## 🛠️ Technologies Used
- **HTML5**: Semantic structure and layout.
- **CSS3**: Custom styling, CSS Grid/Flexbox, and vanilla CSS variables (no external frameworks like Tailwind/Bootstrap used).
- **JavaScript (Vanilla)**: DOM manipulation, Intersection Observer API for scroll animations, and dynamic navigation.

## 🚀 How to Run & Access the Project

Because this project is built with pure HTML, CSS, and JavaScript, there are **no complex installations, build steps, or servers required**. 

### Method 1: Direct Access (Easiest)
1. Open the project folder in your computer's File Explorer.
2. Double-click the **`index.html`** file.
3. The website will instantly open and run perfectly in your default web browser (Chrome, Edge, Firefox, etc.).

### Method 2: Using VS Code (For Development)
If you want to edit the code and see changes update in real-time:
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension from the VS Code marketplace.
3. Right-click on the `index.html` file and select **"Open with Live Server"**.
4. The site will launch on a local development port (e.g., `http://127.0.0.1:5500/index.html`).

## 📁 File Structure
- `index.html` - The main structure and content of the website.
- `style.css` - All styling, responsive media queries, and animation definitions.
- `script.js` - Logic for the mobile menu, scroll tracking, and form interactions.
- `assets/` - Directory containing all project images and the developer avatar.

## 📫 Contact Setup
The contact form is configured to use [Formspree](https://formspree.io/). To receive messages:
1. The form's `action` attribute in `index.html` points to the generated Formspree endpoint.
2. When a user clicks "Send Message", Formspree securely routes the data to the registered email address.
