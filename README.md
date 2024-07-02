# Text Editor Starter Code
# J.A.T.E - Just Another Text Editor

## Description

J.A.T.E is a Progressive Web Application (PWA) that runs in the browser. It meets PWA criteria and features data persistence techniques using IndexedDB. The application can function offline and allows users to create notes or code snippets with or without an internet connection.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technical Acceptance Criteria](#technical-acceptance-criteria)
- [Walkthrough Video](#walkthrough-video)
- [License](#license)

## Installation

1. **Clone the repository**:

   git clone https://github.com/DuleskyJ/TEXT-EDITOR.git 
   cd cautious-meme/Develop

Install dependencies:

npm install

Start the application:

npm run start

## Usage
Open your browser and navigate to http://localhost:3000.

You can start typing your notes or code snippets.

The content will be saved automatically when you click off the window or when the window loses focus.

You can install the application as a PWA by clicking on the "Install" button.

## Technical Acceptance Criteria
- Uses IndexedDB to create an object store and includes both GET and PUT methods.
- The application works without an internet connection.
- Automatically saves content inside the text editor when the DOM window is unfocused.
- Bundled with Webpack.
- Creates a service worker with Workbox that caches static assets.
- The application uses Babel to enable next-gen JavaScript features.
- The application has a generated manifest.json using the WebpackPwaManifest plugin.
- The application can be installed as a Progressive Web Application.

## Walkthrough Video


## License
This project is licensed under the MIT License.