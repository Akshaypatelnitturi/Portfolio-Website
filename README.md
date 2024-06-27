# Portfolio Website
Welcome to the Portfolio Website repository! This README provides an overview of the project structure and instructions for setting up and running the website.
## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
## Project Structure
The project is organized as follows:
portfolio-website/
├── index.html
├── .DS_Store
├── css/
│ ├── style.css
│ └── style2.css
├── fonts/
│ └── custom-fonts/
├── images/
│ └── portfolio-images/
├── js/
│ ├── main.js
│ └── script3.js
├── lib/
│ └── third-party-libraries/
├── scss/
│ ├── style.scss
│ └── additional-styles.scss
└── prepros-6.config
### Files and Directories
- `index.html`: The main HTML file that serves as the entry point of the website.
- `.DS_Store`: System file for macOS, can be ignored or removed.
- `css/`: Contains the compiled CSS files.
  - `style.css`: The primary stylesheet for the website.
  - `style2.css`: An additional stylesheet for alternative styling.
- `fonts/`: Contains custom fonts used in the website.
  - `custom-fonts/`: Directory for storing custom font files.
- `images/`: Contains images used in the website.
  - `portfolio-images/`: Directory for storing portfolio-related images.
- `js/`: Contains JavaScript files.
  - `main.js`: The main JavaScript file for the website.
  - `script3.js`: An additional JavaScript file for extra functionality.
- `lib/`: Contains third-party libraries and plugins.
  - `third-party-libraries/`: Directory for storing external libraries.
- `scss/`: Contains SCSS files.
  - `style.scss`: The main SCSS file for the website.
  - `additional-styles.scss`: Additional SCSS file for extra styles.
- `prepros-6.config`: Configuration file for Prepros, a tool used for preprocessing SCSS to CSS.
## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/portfolio-website.git
   cd portfolio-website
Ensure you have a SCSS compiler installed. If you are using Prepros, import the project into Prepros.
Compile the SCSS files to CSS using your preferred SCSS compiler.
***Usage***
Open index.html in your web browser to view the website.
Customize the content in index.html, scss/style.scss, and js/main.js to personalize your portfolio.
Add your custom fonts to the fonts/custom-fonts/ directory and update the SCSS file to use them.
Add your portfolio images to the images/portfolio-images/ directory and reference them in the HTML and CSS files as needed.
***Customization****
###index.html
index.html is the main entry point of the portfolio website. Open this file in a web browser to view the website. You can customize the content and structure of the webpage here.
###.DS_Store
.DS_Store is a system file created by macOS to store custom attributes of a folder. It can be ignored or removed from the project.
###css/style.css and css/style2.css
style.css and style2.css contain the compiled CSS styles for the website. Ensure to compile your SCSS files to update these CSS files with the latest styles.
###fonts/custom-fonts/
custom-fonts/ directory is for storing custom font files used in the website. Add your custom fonts here and reference them in the SCSS file to apply them to your website.
###images/portfolio-images/
portfolio-images/ directory is for storing images related to your portfolio. Add your images here and reference them in your HTML and CSS files as needed.
###js/main.js and js/script3.js
main.js and script3.js contain the main JavaScript code for the website. You can add interactivity and custom scripts to your website here.Make sure to link these files in your index.html to apply the scripts.
###lib/third-party-libraries/
third-party-libraries/ directory is for storing any external libraries and plugins used in the website. 
Add any third-party JavaScript or CSS libraries here.
###scss/style.scss and scss/additional-styles.scss
style.scss and additional-styles.scss are the main SCSS files for the website. Write your styles here using SCSS syntax, which will be compiled to CSS. Remember to compile these files to generate the updated CSS in the css/ directory.
###prepros-6.config
prepros-6.config is the configuration file for Prepros, a tool used for preprocessing SCSS to CSS. Import this project into Prepros to automatically compile SCSS files to CSS whenever changes are made.



