# Simple HTML Project with Tailwind CSS

This project demonstrates two approaches to using Tailwind CSS in a simple HTML project:

## 🚀 Quick Start (CDN Version)

The easiest way to get started is with the CDN version:

1. Open `index.html` in your browser
2. That's it! The page uses Tailwind CSS via CDN

## 🔧 Advanced Setup (CLI Version)

For better performance and customization, use the CLI version:

### Prerequisites
- Node.js installed on your system

### Installation

1. Install dependencies:
```bash
npm install
```

2. Build the CSS:
```bash
npm run build
```

3. For development with auto-rebuild:
```bash
npm run build-css
```

4. Open `index-cli.html` in your browser

## 📁 Project Structure

```
├── index.html          # CDN version (ready to use)
├── index-cli.html      # CLI version (requires build)
├── package.json        # Node.js dependencies
├── tailwind.config.js  # Tailwind configuration
├── src/
│   └── input.css       # Source CSS with Tailwind directives
└── dist/
    └── output.css      # Generated CSS (after build)
```

## ✨ Features

### CDN Version (`index.html`)
- ✅ Ready to use immediately  
- ✅ No build process required
- ✅ Perfect for prototyping
- ❌ Larger file size
- ❌ Limited customization

### CLI Version (`index-cli.html`)
- ✅ Optimized file size (only used classes)
- ✅ Custom color palette
- ✅ Custom component classes
- ✅ Full Tailwind configuration
- ❌ Requires Node.js and build process

## 🎨 Customization

The CLI version includes:
- Custom primary color palette
- Inter font family
- Reusable component classes (`.btn-primary`, `.card`, etc.)
- Form input styling (`.form-input`)

Edit `tailwind.config.js` and `src/input.css` to customize further.

## 📱 Responsive Design

Both versions include:
- Mobile-first responsive design
- Breakpoint utilities (sm, md, lg, xl)
- Flexible grid layouts
- Responsive navigation

## 🔗 Useful Commands

```bash
# Install dependencies
npm install

# Build CSS once
npm run build

# Watch for changes and rebuild
npm run build-css
```

## 📚 Learn More

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Tailwind CSS CLI](https://tailwindcss.com/docs/installation)
- [Tailwind CSS Components](https://tailwindui.com/components)

Happy coding! 🎉 