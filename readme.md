# Text Editor - Progressive Web Application

 This project is a text editor that runs in the browser. It is a single-page application that meets the PWA criteria. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

# Features
Client-server folder structure<br>
Backend server and client served on npm run start<br>
JavaScript files bundled using webpack<br>
Generated HTML file, service worker, and a manifest file through webpack plugins<br>
Next-gen JavaScript usage<br>
IndexedDB for immediate database storage creation<br>
Content saving with IndexedDB when clicking off of the DOM window<br>
Content retrieval from IndexedDB when reopening the text editor<br>
Installable web application<br>
Registered service worker using workbox<br>
Pre-cached static assets upon loading along with subsequent pages and static assets<br>
Proper build scripts for a webpack application when deployed to Render<br>

# Installation
Clone the repository to your local machine. <br>
Run npm install to install all dependencies.<br>
Run npm run start to start the application.<br>

# Usage
Open the application in your browser. You can create notes or code snippets with or without an internet connection. The content in the text editor will be saved with IndexedDB when you click off of the DOM window. When you reopen the text editor, the content will be retrieved from IndexedDB.

# Deployment
The application is deployed to Render. The deployment includes proper build scripts for a webpack application.