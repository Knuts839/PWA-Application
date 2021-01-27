# PWA-Application
This is a purchase tracking application. It saves transaction title information as well as amount paid for the product or service. This purchase tracker application can run offline by caching the necessary files in the browser's cache folder. It will temporarily store the information you inserted while offline in the browser's index db and once the internet connection is restored it saves the information to MongoAtlas and deletes the information from the browser's index db. Other technologies used: node.js, express, service worker registration and MVC file structure.

This application can run off cached information if connection with the internet is lost. It will save data in index db till connection is restored. Then, it will automatically update mongo db Atlas. The technologies used in the development of this application are mongo db and express for the local host testing and development and Mongo Atlas and node express for the deployed application. This application can be used in offline mode to log purchases and when internet connection is regained, send the data logged in index db to your database for long-term storage. This application can be installed as a mobile/desktop app, so user always has access to it. 



