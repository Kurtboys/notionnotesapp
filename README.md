# What's Next - Notion Embeddable Notes App

A lightweight, embeddable notes app designed to work within Notion pages. Perfect for brainstorming and quick notes even when your Notion page is locked.

## Features

- **Rich Text Editing**
  - Bold, Italic, Underline formatting
  - Multiple font sizes (Small, Normal, Large, X-Large, XX-Large)
  - Text color (10 Notion-inspired colors)
  - Highlight/background color (10 colors)
  - Bullet and numbered lists
  - Clear formatting option

- **Auto-Save**: Notes are automatically saved to local storage
- **Keyboard Shortcuts**: Ctrl+B (Bold), Ctrl+I (Italic), Ctrl+U (Underline), Ctrl+S (Save)
- **Multiple Notes**: Use URL hash to create separate note instances
- **Responsive Design**: Works on desktop and mobile

## Deployment

### Option 1: GitHub Pages (Recommended)

1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select "Deploy from a branch" and choose `main` (or `master`)
4. Your app will be available at `https://yourusername.github.io/notionnotesapp/`

### Option 2: Netlify

1. Connect your GitHub repository to Netlify
2. Deploy with default settings
3. Your app will be available at your Netlify URL

### Option 3: Vercel

1. Import your repository to Vercel
2. Deploy with default settings
3. Your app will be available at your Vercel URL

## Embedding in Notion

1. Deploy the app using one of the options above
2. In Notion, type `/embed` and select "Embed"
3. Paste your deployed URL (e.g., `https://yourusername.github.io/notionnotesapp/`)
4. Resize the embed block to your preferred size

### Creating Multiple Note Instances

Add a unique hash to the URL to create separate note instances:

- `https://yoursite.com/notionnotesapp/#project1`
- `https://yoursite.com/notionnotesapp/#ideas`
- `https://yoursite.com/notionnotesapp/#todo`

Each hash creates a separate note stored in local storage.

## Local Development

Simply open `index.html` in your browser. No build process required!

```bash
# Or use a simple HTTP server
npx serve .
# or
python -m http.server 8000
```

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## Data Storage

Notes are stored in the browser's local storage. This means:
- Notes persist across sessions
- Notes are specific to the browser/device
- Clearing browser data will delete notes

## License

MIT License
