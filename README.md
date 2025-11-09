# Pixellot Guides

A modern, techy documentation hub for Pixellot workflow guides.

## Features

- 🎨 Modern, professional design with dark theme
- 📱 Fully responsive layout
- 🌐 Multi-language support (English & Hebrew)
- ⚡ Fast, static site - no build process required
- 🔧 Easy to add new guides

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select the main branch as source
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Vercel

1. Import this repository to Vercel
2. Vercel will automatically detect it as a static site
3. Deploy - no configuration needed!

## Adding New Guides

To add a new guide:

1. Add your HTML guide file to the root directory
2. Update the `guides` array in `index.html`:

```javascript
const guides = [
    // ... existing guides
    {
        id: 'your-guide-id',
        title: 'Your Guide Title',
        description: 'Brief description of the guide',
        language: 'English',
        langCode: 'EN',
        file: 'YourGuideFile.html',
        icon: '📹'
    }
];
```

That's it! The new guide will automatically appear on the homepage.

## Structure

```
.
├── index.html              # Main landing page
├── SendLoggingVidswap_ENG.html
├── SendLoggingVidswap_HEB.html
└── README.md
```

## License

MIT
