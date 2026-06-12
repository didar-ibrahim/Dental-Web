# Dental Web Project

A static dental clinic website project built with HTML, CSS, and Bootstrap.

## Project files

- `bootstrapwebsite2.html` - main homepage layout
- `About.html` - about the clinic page
- `Contact.html` - contact page
- `Gallary.html` - gallery page
- `Register.html` - registration or appointment form page
- `bootstrapwebsite2.css` - custom styles for the site
- `bootstrap-5.3.2-dist/` - local Bootstrap 5 CSS and JS files
- `img/` - project images used in the website

## How to run

### Option 1: Open directly in browser
1. Open the project folder in File Explorer.
2. Double-click any `.html` file, for example `bootstrapwebsite2.html`.
3. The page will open in your default web browser.

### Option 2: Use a local server
This is recommended for development and for sites that load resources more reliably.

#### With VS Code Live Server
1. Install the Live Server extension in VS Code.
2. Open the project folder in VS Code.
3. Right-click `bootstrapwebsite2.html` and choose `Open with Live Server`.

#### With Python
1. Open a terminal in the project folder.
2. Run:
   ```powershell
   python -m http.server
   ```
3. Open `http://localhost:8000` in your browser.

## Notes

- This is a frontend-only website. No backend or server-side code is included.
- The `bootstrap-5.3.2-dist/` folder is included so the site works offline without relying on CDN resources.
- You can modify the HTML, CSS, and image files freely to customize the site.
