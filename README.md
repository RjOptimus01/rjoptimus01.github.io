# Portfolio Website

A modern, responsive portfolio website built using HTML, CSS, and JavaScript. The project focuses on clean UI, smooth user experience, and responsive design while showcasing professional web development practices.

## Live Demo

https://rjoptimus01.github.io/

## Features

- Responsive layout for desktop, tablet, and mobile devices
- Modern and clean user interface
- Sticky navigation bar
- Mobile navigation menu
- Smooth scrolling
- Scroll reveal animations
- Contact form powered by EmailJS
- Resume download
- Social media integration
- Cross-browser compatibility
- Optimized performance

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- EmailJS
- GitHub Pages

## Project Structure

```text
.
├── assets/
│   ├── images/
│   ├── icons/
│   └── resume/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/RjOptimus01/RjOptimus01.github.io.git
```

Navigate to the project directory:

```bash
cd RjOptimus01.github.io
```

Open `index.html` directly in your browser or run the project using a local development server such as VS Code Live Server.

## EmailJS Configuration

This project uses EmailJS for the contact form.

If you plan to use this project as a template:

1. Create an EmailJS account.
2. Create your own Email Service.
3. Create your own Email Template.
4. Generate your own Public Key.
5. Replace the EmailJS credentials in `script.js`.

Example:

```javascript
emailjs.init({
    publicKey: "YOUR_PUBLIC_KEY"
});

emailjs.send(
    "YOUR_SERVICE_ID",
    "YOUR_TEMPLATE_ID",
    {
        from_name: name,
        from_email: email,
        message: message
    }
);
```

**Important:** Do not use the EmailJS credentials from this repository in your own deployment.

## Deployment

This project is deployed using GitHub Pages.

To deploy your own version:

1. Fork or clone the repository.
2. Push your changes to GitHub.
3. Enable GitHub Pages from the repository settings.
4. Configure your own EmailJS credentials before deploying.

## Customization

You can customize:

- Color palette
- Fonts
- Images
- Resume
- Social media links
- Contact information
- EmailJS configuration

## Important

If you fork or clone this repository:

- Create your own EmailJS account.
- Generate your own Service ID, Template ID, and Public Key.
- Replace the EmailJS credentials before deploying.

Otherwise, your contact form will not work correctly and may send requests to the original owner's EmailJS service.
