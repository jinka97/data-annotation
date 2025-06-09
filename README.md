# Data Annotation Platform

A web-based platform for annotating CSV data with a mobile-friendly interface, theme toggle, and privacy notice.

## Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/data-annotation-platform.git
   cd data-annotation-platform
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the CSS:
   ```bash
   npm run build
   ```

4. To watch for changes during development:
   ```bash
   npm run watch
   ```

## Project Structure

- `dist/`: Contains production-ready files (`index.html`, `privacy.html`, `output.css`).
- `src/input.css`: Source CSS file with Tailwind directives.
- `tailwind.config.js`: Tailwind configuration.
- `postcss.config.js`: PostCSS configuration.
- `package.json`: Project dependencies and scripts.

## Deployment to GitHub Pages

1. Ensure the `dist` folder contains `index.html`, `privacy.html`, and `output.css`.
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update project with production-ready Tailwind CSS"
   git push origin main
   ```
3. Configure GitHub Pages in your repository settings to deploy from the `dist` folder or root directory.

## Testing

1. Open `dist/index.html` in a browser or serve it locally (e.g., using `npx http-server dist`).
2. Verify no console errors (F12 → Console).
3. Test features:
   - Upload a sample CSV and annotate data.
   - Check privacy notice visibility and functionality.
   - Toggle between light and dark themes.
   - Clear annotations and start a new session.
   - Test on mobile (Chrome DevTools → Device Toolbar).

## Customization

- Update `[your-email@example.com]` in `dist/privacy.html`.
- Modify `tailwind.config.js` to add custom Tailwind themes or plugins.
- Adjust styles in `dist/index.html` `<style>` block for custom CSS.

## License
ISC