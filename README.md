# Patrick Mellor - Portfolio Website

Welcome to my personal portfolio website! This is a modern, responsive website showcasing my skills and projects.

## Features

- 🎨 Modern, eye-catching design with gradient animations
- 📱 Fully responsive layout (mobile, tablet, desktop)
- ✨ Smooth animations and transitions
- 🎯 Sticky navigation with smooth scrolling
- 💼 Sections for About, Projects, and Contact
- ⚡ Lightweight and fast (pure HTML/CSS/JavaScript)

## Getting Started

### Prerequisites

You only need a modern web browser. No server setup required!

### Running Locally

There are several ways to run this website locally:

#### Option 1: Using Python (Recommended)

If you have Python 3 installed, navigate to the project directory and run:

```bash
python -m http.server 8000
```

Then open your browser and visit: `http://localhost:8000`

#### Option 2: Using Python 2

If you have Python 2:

```bash
python -m SimpleHTTPServer 8000
```

Then open your browser and visit: `http://localhost:8000`

#### Option 3: Using Node.js

If you have Node.js installed, you can use `http-server`:

```bash
npm install -g http-server
http-server
```

Then open your browser and visit the URL shown in the terminal (usually `http://localhost:8080`)

#### Option 4: Using Live Server (VS Code Extension)

If you're using Visual Studio Code:

1. Install the "Live Server" extension by Ritwick Dey
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your browser will open automatically

#### Option 5: Direct File Opening

Simply double-click `index.html` to open it in your default browser (simplest option, but without hot reload).

## Project Structure

```
patrickmellor-website/
├── index.html       # Main HTML file with page structure
├── style.css        # Styling and animations
├── script.js        # Interactive functionality
├── README.md        # This file
└── .git/           # Version control
```

## Customization

### Update Your Information

Edit `index.html` to customize:
- Your name and title
- About section content
- Projects and project descriptions
- Contact email and social links

### Modify Colors

Edit `style.css` CSS variables at the top:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    --dark-bg: #0f0f1e;
    --light-bg: #1a1a2e;
    --text-light: #e0e0e0;
    --text-dark: #121212;
}
```

### Add More Content

Simply add new sections to `index.html` following the existing pattern, and style them in `style.css`.

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (Vanilla)** - Interactive features without dependencies

## Browser Support

Works on all modern browsers including:
- Chrome/Chromium
- Firefox
- Safari
- Edge
