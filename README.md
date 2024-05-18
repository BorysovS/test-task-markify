# Markify

This project is a web page for Markify, a marketing consulting service. It includes various sections
such as header, hero, partners, about, services, agency, and footer.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Live Demo](#live-demo)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [License](#license)

## Installation

To get started with this project, clone the repository to your local machine

## Usage

Using Live Server This project is designed to be run using the Live Server extension in Visual
Studio Code (VS Code). Follow these steps to set it up:

Install Live Server Extension:

Open VS Code. Go to the Extensions view by clicking the Extensions icon in the Sidebar or by
pressing Ctrl+Shift+X. Search for Live Server by Ritwick Dey and install it. Open the Project
Folder:

Open the project folder in VS Code by selecting File > Open Folder and navigating to your project
directory. Start Live Server:

Open the index.html file in VS Code. Right-click on the index.html file and select Open with Live
Server. Your default browser should open and display the web page. If not, you can manually open
your browser and navigate to http://127.0.0.1:5500. Without Live Server If you prefer not to use
Live Server, you can simply open the index.html file directly in your browser. However, note that
some features might not work as expected without a local server.

## Live Demo

You can view a live demo of the project at the following URL:

Live Demo

https://borysovs.github.io/test-task-markify/

## Project Structure

markify/ │ ├── css/ │ ├── main.css │ └── main.min.css │ ├── img/ │ ├── header/ │ ├── hero/ │ ├──
partners/ │ └── services/ │ ├── js/ │ └── modal.js │ ├── index.html ├── README.md └──
.browserslistrc

css/: Contains the main CSS files for styling the web page. img/: Contains images used throughout
the website. js/: Contains JavaScript files for additional functionality. index.html: The main HTML
file that structures the web page. README.md: This file, providing information about the project.
.browserslistrc: Configuration file for specifying the browser versions supported by this project.

## Requirements

To continue working on the project and add cross-browser compatibility to the styles, the following
is needed:

Node.js (https://nodejs.org/) npm (usually comes with Node.js)

Installing Dependencies If you are making changes to the styles or continuing to develop the
project, you need to install dependencies and recompile the styles. Follow these steps:

Open the terminal and navigate to the project directory. Run the following command to install all
necessary dependencies: npm install

Compiling Styles After making changes to the styles or adding new ones, you need to ensure their
cross-browser compatibility. To do this, run the following command to compile the styles:

npm run build:css

This command will add the necessary autoprefixes to your styles for cross-browser compatibility.

## License

This project is licensed under the MIT License.
