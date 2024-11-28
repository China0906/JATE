# JATE

## Description
This project is a browser-based text editor that meets the criteria of a Progressive Web App (PWA). The single-page application (SPA) is designed to provide a seamless text editing experience with robust data persistence techniques, ensuring functionality even when offline. The application uses the idb package to interact with an IndexedDB database for efficient data storage and retrieval.

### Key Features
Progressive Web App: Fully PWA-compliant with offline capabilities.
Data Persistence: Multiple redundancy techniques ensure data persistence regardless of browser support for certain APIs.
Offline Functionality: Users can create and edit text without an internet connection.
IndexedDB Integration: Implements idb, a lightweight IndexedDB wrapper used by industry leaders like Google and Mozilla.
Deployment on Render: The full-stack application is deployed on Render, following best practices outlined in the Render Deployment Guide.
Technologies Used
Frontend: JavaScript, HTML, CSS
Backend: Node.js, Express.js
Database: IndexedDB (via idb package)
Deployment: Render
Other: Service workers, Webpack

#### Installation
Clone the repository:

bash
Copy code
git clone <https://github.com/China0906/JATE>
cd <JATE>
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start

##### Usage
Open the application in your browser.
Use the text editor to create or modify text.
Save your work, which is stored in the IndexedDB database.
Install the app as a PWA to use it offline.
##### Data Persistence Techniques
This application ensures data redundancy using:

IndexedDB: Primary data storage, accessed via the idb package.
Local Storage: As a fallback for basic persistence.
Service Workers: To cache assets and ensure offline functionality.

###### Deployment
The application is deployed on Render. Follow the instructions in the Render Deployment Guide to replicate or update the deployment.

#### Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Description of your changes"
Push your branch:
bash
Copy code
git push origin feature-name
Open a pull request.
##### License
This project is licensed under the MIT License. See the LICENSE file for details.

##### Acknowledgements
This challenge was assited with help of TA Diem Ly as class
Render: Hosting platform for the deployed application.

