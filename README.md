# Markdown to HTML Converter

This repository holds a React application. It converts Markdown into HTML. The application was built in a Google Colab environment.

## Project Steps

The project setup and build happen in these steps:

### Setup

1.  **Node.js and npm**: Node.js and npm (Node Package Manager) are installed first. This provides a JavaScript runtime and a way to manage packages. A GPG key from NodeSource is fetched to check package integrity.
2.  **Check Installation**: Node.js and npm versions are checked to confirm installation.

### Project Creation and File Handling

1.  **Make Directories**: A main project directory (`my-markdown-converter`) and a source directory (`src`) are created.
2.  **Upload App File**: You upload your `MarkdownToHtmlApp.jsx` file. This file is then renamed to `App.jsx` and moved into the `src` directory.

## Configuration Files

The application uses specific configuration files:

* **`package.json`**: This file lists project details, scripts, and dependencies. It includes `react`, `react-dom`, `lucide-react`, and `marked`. It also lists development tools like `vite`, `@vitejs/plugin-react`, `autoprefixer`, `eslint`, `postcss`, and `tailwindcss`.
* **`index.html`**: This is the main HTML file for the web application.
* **`src/main.jsx`**: This file starts the React application. It renders the `App` component and imports global styles.
* **`src/index.css`**: This file imports Tailwind CSS parts: base, components, and utilities.
* **`tailwind.config.js`**: This file tells Tailwind CSS where to look for styling in your code.
* **`postcss.config.js`**: This file sets up PostCSS with Tailwind CSS and Autoprefixer.
* **`vite.config.js`**: This file configures Vite for React. It sets the `base` path for GitHub Project Pages (`/cbk-markdown-to-html/`) and sets the build output directory as `docs`.

## Building and Output

1.  **Install Dependencies**: All project dependencies are installed using `npm install`.
2.  **Build Application**: The React application is built using `npm run build`. This makes static files.
3.  **Output Location**: The built application is in the `docs` folder. This folder can be put on GitHub Pages.
4.  **Download Files**: The `docs` folder is zipped and can be downloaded from the Colab environment.

## Publishing to GitHub Pages

1.  **Create GitHub Repository**: Create a new public repository on GitHub.
2.  **Upload `docs` Folder**: Unzip the downloaded `docs.zip` file. Upload the content of the `docs` folder to the root of your GitHub repository.
3.  **Configure GitHub Pages**: In your GitHub repository settings, go to the "Pages" section. Choose the `main` branch (or your primary branch) and the `/docs` folder as the source for GitHub Pages. Save your changes.
4.  **Access Your Page**: Your application will be live at `https://<your-username>.github.io/<your-repository-name>/`. It may take a few minutes for the page to become active.
