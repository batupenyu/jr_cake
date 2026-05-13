# Roll Cake - Sweet Treats by JR

A static website for a roll cake business built with HTML, Tailwind CSS, and vanilla JavaScript.

## 📋 Prerequisites

- [Node.js](https://nodejs.org/) v18+ (for local dev, build, and Lighthouse)

## 📁 Project Structure

```
.
├── index.html          # Main homepage
├── admin.html          # Admin page
├── cake.jpeg           # Hero image
├── Strawberry Dream.jpeg # Product image
├── lighthouserc.json   # Lighthouse CI config
├── package.json        # Project dependencies & scripts
└── README.md           # This file
```

## 🛠️ Local Development

```bash
npm install
npm run dev       # Start dev server (Vite)
npm run build     # Build for production → dist/
npm run preview   # Preview production build
```

## 🔍 Lighthouse Audit

```bash
npm run lhci
```

Runs a Lighthouse CI audit using the config in `lighthouserc.json`. Results are uploaded to temporary public storage.

## 🚀 Deploy to Netlify

### Option 1: Drag and Drop (Recommended for beginners)
1. Run `npm run build` to generate the `dist/` folder
2. Go to [netlify.com/drop](https://app.netlify.com/drop)
3. Drag and drop the `dist/` folder onto the upload area

### Option 2: Connect via Git
1. Push this repository to GitHub/GitLab/Bitbucket
2. Go to [netlify.com](https://app.netlify.com) → "New site from Git"
3. Connect your Git provider and select this repository
4. Set build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
5. Click "Deploy site"

### Option 3: Netlify CLI
```bash
npm install -g netlify-cli
netlify login
netlify init
netlify deploy --prod --dir=dist
```

## ✨ Features

- Responsive design with Tailwind CSS
- Interactive cart functionality
- WhatsApp integration for orders
- Smooth scrolling navigation
- Toast notifications
- Mobile-friendly layout

## 🔧 Customization

- Update product information in the menu section of `index.html`
- Change colors by modifying the Tailwind config in the `<script>` tag
- Update WhatsApp number via the `WA_NUMBER` constant in the JavaScript
- Replace images with your own product photos

## 📱 Supported Browsers

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

---

*Built with ❤️ for Sweet Treats by JR*
