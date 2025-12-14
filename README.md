# 🚗 AGGELOS Rentals - React Website

A modern, SEO-optimized car rental website for **AGGELOS Rentals** serving Athens, Piraeus Port, and Athens Airport.

## 🌐 Live Website

**[aggelosrentals.gr](https://aggelosrentals.gr)**

## ✨ Features

- 🎨 **Modern UI/UX** - Sleek, responsive design with smooth animations
- 🌍 **Bilingual** - Full Greek (EL) and English (EN) language support
- 📱 **Mobile-First** - Fully responsive across all devices
- 🔍 **SEO Optimized** - Schema markup, meta tags, and structured data
- ⚡ **Fast Performance** - Vite-powered build with optimized assets
- 📍 **Multiple Locations** - Athens Airport, Piraeus Port, Athens Center
- 📝 **Blog Section** - SEO-focused articles for organic traffic
- 💬 **WhatsApp Integration** - Floating contact button

## 🛠️ Tech Stack

- **React 18** - UI Framework
- **Vite** - Build tool & dev server
- **React Router v6** - Client-side routing
- **Framer Motion** - Animations
- **React Helmet Async** - SEO & meta management
- **React Icons** - Icon library

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/fwtiskoukakis/AGGELOS-RENTALS-WEBSITE-REACT.git

# Navigate to project directory
cd AGGELOS-RENTALS-WEBSITE-REACT

# Install dependencies
npm install
```

## 🚀 Development

```bash
# Start development server
npm run dev

# The app will be available at http://localhost:5173
```

## 🏗️ Build for Production

```bash
# Create production build
npm run build

# Preview production build locally
npm run preview
```

## 📁 Project Structure

```
src/
├── components/
│   ├── common/          # Reusable components (WhatsApp, SEO, etc.)
│   ├── Layout/          # Header, Footer, Layout wrapper
│   ├── Schema/          # JSON-LD Schema components
│   └── sections/        # Page sections (Hero, Benefits, etc.)
├── data/
│   ├── blogContent.js   # Blog articles content
│   ├── blogPosts.js     # Blog posts metadata
│   └── vehicles.js      # Vehicle fleet data
├── i18n/
│   └── locales/         # Translation files (en.json, el.json)
├── pages/               # Route pages
├── styles/              # Global styles & variables
├── App.jsx              # Main app component
├── main.jsx             # App entry point
└── routes.jsx           # Route definitions
```

## 🌐 Available Routes

| Route | Description |
|-------|-------------|
| `/` | Homepage |
| `/fleet` | Vehicle Fleet |
| `/monthly-rentals` | Monthly Rental Plans |
| `/athens-airport` | Athens Airport Location |
| `/piraeus-port` | Piraeus Port Location |
| `/athens-center` | Athens Center Location |
| `/athens-airport-to-piraeus` | Airport to Port Transfer |
| `/faq` | Frequently Asked Questions |
| `/contact` | Contact Page |
| `/blog` | Blog Section |
| `/blog/:slug` | Individual Blog Posts |

## 🔧 Environment Variables

No environment variables required for basic development.

## 📄 License

© 2026 AGGELOS Rentals. All rights reserved.

## 👨‍💻 Developer

Built with ❤️ by [Anotherseoguru.com](https://anotherseoguru.com)
