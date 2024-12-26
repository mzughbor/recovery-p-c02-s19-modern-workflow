# Webpack + Babel Boilerplate

## Description
This boilerplate is designed to help you kickstart your new project using Webpack and Babel with a modern workflow. It includes configurations for development and production environments.

## Features
- Modern JavaScript (ES6+) support via Babel
- Development server with hot module replacement (HMR)
- Optimized production build
- Easy-to-use npm scripts

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run server
   ```

4. Build for production:
   ```bash
   npm run build
   ```

---

## Project Structure
```plaintext
.
├── src
│   ├── index.js         # Entry point
│   └── assets           # Static assets (e.g., images, fonts)
├── dist                 # Compiled files for production
├── .babelrc             # Babel configuration
├── .gitignore           # Git ignore file
├── package.json         # npm scripts and dependencies
├── webpack.config.js    # Webpack configuration
└── README.md            # Project documentation
```
---

## Example Files

### `src/index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Webpack + Babel Boilerplate</title>
</head>
<body>
  <h1>Welcome to the Webpack + Babel Boilerplate! 🚀</h1>
</body>
</html>
```

---

## Scripts in `package.json`
```json
"scripts": {
  "build": "webpack --mode production",
  "server": "webpack serve --mode development"
}
```

---

## Happy Coding! 🚀✨
