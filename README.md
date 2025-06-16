# Regina Cloman-Moore Author Website

A professional author website for Regina Cloman-Moore, showcasing her books and providing information about her work.

![Regina Cloman-Moore Website Screenshot](https://hdhbkzfn.manus.space/screenshot.png)

## Live Demo

The live website is available at: [https://hdhbkzfn.manus.space](https://hdhbkzfn.manus.space)

## Features

- Responsive design for all device sizes
- Separate sections for adult and children's books
- Author biography page
- Contact form for reader inquiries
- Newsletter signup
- Burgundy color scheme as requested by the author

## Books Featured

- Florida Peppermint Goes To School
- I Know My Father's Voice
- Grandma's Lap

## Technology Stack

- React.js
- Tailwind CSS
- React Router

## Project Structure

```
regina-cloman-moore-website/
├── public/                  # Public assets
├── src/                     # Source code
│   ├── assets/              # Images and media files
│   ├── components/          # Reusable UI components
│   │   ├── Header.js        # Site navigation header
│   │   └── Footer.js        # Site footer with newsletter signup
│   ├── pages/               # Page components
│   │   ├── HomePage.js      # Landing page
│   │   ├── BooksPage.js     # Book listings
│   │   ├── AboutPage.js     # Author biography
│   │   └── ContactPage.js   # Contact form
│   ├── App.js               # Main application component
│   └── index.js             # Application entry point
├── package.json             # Project dependencies
├── tailwind.config.js       # Tailwind CSS configuration
└── postcss.config.js        # PostCSS configuration
```

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/regina-cloman-moore-website.git
   cd regina-cloman-moore-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view the website in your browser.

### Building for Production

To create a production build:

```bash
npm run build
```

The build files will be created in the `build/` directory.

## Deployment

### Deploying to Netlify

#### Option 1: Deploy via GitHub (recommended for ongoing updates)

1. Push your code to GitHub
2. Log in to [Netlify](https://www.netlify.com/)
3. Click "New site from Git"
4. Select GitHub and authorize Netlify
5. Select your repository
6. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `build`
7. Click "Deploy site"

#### Option 2: Direct upload (simpler for one-time deployment)

1. Create a production build with `npm run build`
2. Go to [Netlify](https://www.netlify.com/) and create an account
3. Click "Add new site" → "Deploy manually"
4. Drag and drop the `build` folder
5. Your site will be deployed immediately

## Customization

### Changing Colors

The color scheme can be modified in the `tailwind.config.js` file:

```javascript
theme: {
  extend: {
    colors: {
      burgundy: '#800020',
      cream: '#FFF8DC',
      gold: '#FFD700',
      darkGray: '#333333',
    },
  },
},
```

### Adding New Books

To add new books, update the `BooksPage.js` file with new book information and add book cover images to the `src/assets` directory.

## License

This project is proprietary and belongs to Regina Cloman-Moore. All rights reserved.

## Contact

For questions about the website, please contact Regina Cloman-Moore through the contact form on the website.

---

Created with ❤️ for Regina Cloman-Moore
