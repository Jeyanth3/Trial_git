# Welcome Page Project

A modern, interactive welcome page built with **HTML**, **Tailwind CSS**, and **TypeScript**.

## Features

- 🎨 **Gradient Background** - Beautiful purple to pink to red gradient
- ✨ **Animations** - Pulse and bounce animations on interaction
- 📱 **Responsive Design** - Works seamlessly on all screen sizes
- 🎯 **Interactive Elements** - Click the "Hi" text to toggle animations
- 🖥️ **TypeScript Support** - Type-safe JavaScript with type annotations
- ⚡ **CDN-based Tailwind CSS** - No build process required

## Project Structure

```
Trial_git/
├── index.html          # Main welcome page
├── Helloworld.txt      # Additional file
└── README.md           # Project documentation
```

## Getting Started

### Quick Start

1. Open `index.html` in your web browser
2. The welcome page will display with animations
3. Click on the "Hi" text to see the bounce animation

### No Installation Required

This project uses Tailwind CSS via CDN, so no npm installation or build process is needed!

## How It Works

### HTML Structure
- Simple, semantic HTML with Tailwind CSS classes
- ID-based element selection for JavaScript interaction

### Styling with Tailwind CSS
```html
<body class="bg-gradient-to-r from-purple-500 via-pink-500 to-red-500 min-h-screen flex items-center justify-center">
```

### TypeScript Functionality
```javascript
const welcomeText = document.getElementById('welcome-text') as HTMLElement;

welcomeText.addEventListener('click', () => {
    welcomeText.classList.toggle('animate-bounce');
    console.log('Welcome text clicked!');
});
```

## Customization

### Change Colors
Modify the gradient classes in `index.html`:
```html
class="bg-gradient-to-r from-blue-500 via-green-500 to-yellow-500"
```

### Adjust Text Size
Change the Tailwind text size utility:
```html
class="text-8xl"  <!-- Change to text-6xl, text-9xl, etc. -->
```

### Add More Content
Add additional elements inside the `<div class="text-center">` container.

## Browser Compatibility

Works on all modern browsers that support:
- HTML5
- ES6 JavaScript
- CSS3 Animations
- Gradient backgrounds

## Technologies Used

- **HTML5** - Markup language
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript/TypeScript** - Interactivity and type safety
- **CDN** - Content Delivery Network for Tailwind

## Author

Created for CO2060 - Software Systems Design Project (3rd Semester)

## License

Open source - feel free to use and modify!
