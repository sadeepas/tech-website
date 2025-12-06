
# FutureTech Nexus 🌌

**FutureTech Nexus** is a futuristic, sci-fi themed personal portfolio template designed to showcase projects and blogs with a unique visual style. Built with a focus on immersive UI, it features a "Proton Tunnel" background animation, neon aesthetics, and a fully responsive layout.


## ✨ Features

*   **Immersive Design:** Custom CSS "Proton Tunnel" background animation.
*   **Responsive Layout:** Fully responsive grid system built with Tailwind CSS.
*   **Theme System:** Functional Dark/Light mode toggler with state persistence.
*   **Interactive UI:**
    *   Smooth scrolling navigation.
    *   Mobile hamburger menu.
    *   Hover effects and card animations.
*   **Contact Form:** Integrated structure for Formspree (or similar services) for functional emails without a backend.
*   **Zero Build Step:** Uses Tailwind CSS via CDN for instant deployment—no Node.js or build process required.

## 🛠 Tech Stack

*   **HTML5**
*   **CSS3** (Custom Animations + Variables)
*   **Tailwind CSS** (via CDN)
*   **JavaScript** (Vanilla ES6)
*   **FontAwesome** (Icons)
*   **Google Fonts** (Inter)

## 🚀 Getting Started

Since this project uses the Tailwind CDN, there are no dependencies to install.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/futuretech-nexus.git
    ```
2.  **Open the project:**
    Simply locate `index.html` in your file explorer and double-click to open it in your browser.

## ⚙️ Customization Guide

### 1. Setting up the Contact Form
To make the contact form functional, you need to connect it to an email service like Formspree.
1.  Go to [Formspree](https://formspree.io/).
2.  Create a new form and copy your unique Endpoint URL.
3.  Open `index.html` and locate the `<form>` tag (approx line 235).
4.  Replace the `action` attribute:
    ```html
    <form id="contactForm" action="https://formspree.io/f/YOUR_UNIQUE_ID_HERE" method="POST" ...>
    ```

### 2. Changing Images
Replace the placeholder images in the `src` attributes within the Gallery section. Ensure your images are placed in the root folder or an `/images` subfolder.
```html
<img src="your-image-name.jpg" alt="Description" ...>
```

### 3. Modifying Colors
The core colors are defined as CSS variables in the `<style>` block. Change these hex codes to alter the entire theme:
```css
:root {
  --primary-color: #1f5f8c;
  --secondary-color: #4361ee;
  --accent-color: #ff6565;
}
```

## 📂 Project Structure

```text
/
├── index.html          # Main application file (HTML, CSS, JS)
├── README.md           # Documentation
└── (Your images)       # Add your image files here
```

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🌟 Acknowledgements

*   [Tailwind CSS](https://tailwindcss.com)
*   [Font Awesome](https://fontawesome.com)
*   [Formspree](https://formspree.io)
```
