Description

The Text Editor is a progressive web application (PWA) designed to allow developers to create and save notes or code snippets, both online and offline. This single-page application (SPA) leverages IndexedDB for data persistence, ensuring that content is saved even when the app is used without an internet connection. The application meets all PWA criteria, making it installable on desktop devices and offering a seamless offline experience. The project also utilizes webpack to bundle the application, ensuring a smooth and modern development workflow.
Features

    Full offline functionality using IndexedDB for data storage and retrieval.
    Bundled JavaScript files using webpack, including plugins for generating HTML, service workers, and manifest files.
    PWA installation option, allowing users to download and install the application as a desktop icon.
    Automatic saving of text editor content when clicking off the window.
    Retrieval of saved content when reopening the application.
    Service worker registration using Workbox to cache static assets and pages.
    Responsive, modern user interface optimized for a smooth experience both online and offline.

Technologies

    Node.js & Express.js: For managing the back-end server and routing.
    IndexedDB & idb Package: For managing client-side storage of text editor data.
    Webpack: For bundling JavaScript, generating HTML, and managing service workers and manifest files.
    Workbox: For creating and managing service workers and caching strategies.
    PWA (Progressive Web App): Ensures offline functionality and installability on desktop.
    Render: For deploying the full-stack application in a production environment.

Deployed Link

    https://maucap20.github.io/TextEditor/ 
    