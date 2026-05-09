# HAIDER REAL ESTATE Landing Page

## Run Locally

1. Install dependencies:

```bash
npm install
```

2. Start the local development server:

```bash
npm run dev
```

Vite will serve the website from `index.html` and open it at a localhost address such as `http://127.0.0.1:5173/`.

3. Build the production files:

```bash
npm run build
```

## File Connections

- `index.html` loads `style.css` directly.
- `index.html` loads `main.js` directly.
- Images are referenced from the project root using their existing filenames.
- WhatsApp links use `https://wa.me/97474459589`.

## Deploy To Vercel

1. Make sure the project builds locally:

```bash
npm install
npm run build
```

2. Push this project to GitHub.
3. Import the GitHub repository into Vercel.
4. Use these Vercel settings:

```text
Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
```

Vercel will install dependencies, run the build command, and deploy the generated `dist` folder.
