# 3D Iris Classifier and SVM Decision Boundary

## Introduction

This project is an interactive 3D visualization tool that demonstrates the classification process of the iris flower dataset and uses the support vector machine (SVM) algorithm to present decision boundaries. This tool is designed to help users understand how SVM classifiers distinguish different iris species and characteristics in three-dimensional space.

Check out the demo [here](https://quantumwings.github.io/SVM-3D-Iris-Classifier/).

## Main functions

1. 3D scatter plot showing iris flower samples and characteristics
2. Interactive SVM decision boundary plane
3. Animation effects of iris varieties and characteristics
4. Hover information displays data point details
5. Responsive design to adapt to different screen sizes
6. Data set information modal box

## Installation and Setup Guide

### Environmental requirements

- Modern web browser (supports HTML5, CSS3 and ES6+)
- Network connection (for loading external script libraries)

### How to use

1. Download the entire HTML file to your computer.
2. Open the HTML file using a modern web browser (such as the latest version of Chrome, Firefox, Safari or Edge).
3. No additional installation steps are required, the page will automatically load all necessary scripts and styles.
4. Wait for the page to fully load and then you can start using the 3D Iris Classifier.

## Instructions for use

### Operation steps

1. Once the page loads, you will see a 3D scatter plot showing iris flower samples and characteristics.
2. Use your mouse or trackpad to rotate, zoom, and pan the 3D view.
3. Click the button in the control panel on the right (or bottom on mobile devices) to trigger the animation:
 - Varieties Buttons (Iris Mountain, Iris Varicolor, Iris Virginia)
 - Feature buttons (sepal length, sepal width, petal length, petal width)
4. Use the "Reset Animation" button to return all points to their original positions.
5. Click the "Show Information" button to view detailed information about the iris data set.

### Example

1. Click the "Mountain Iris" button:
 - All Iris samples will be moved above the SVM decision boundary plane
 - Other varieties and traits will move below the plane

2. Click the "Sepal Length" button:
 - All sepal length feature points will be moved above the SVM decision boundary plane
 - Other traits and all breed samples will be moved below the plane

## Project structure

- `index.html`: Contains all the necessary HTML, CSS and JavaScript code to build and display an interactive interface for the 3D Iris classifier.

The project adopts Model-View-Controller (MVC) architecture:

- Model (IrisClassifierModel): manages data and business logic
- View (IrisClassifierView): handles the presentation layer
- Controller (IrisClassifierController): coordinates the interaction between the model and the view

## Contribution Guidelines
If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request.

## Authorization information
This project is licensed under the terms of [MIT](https://opensource.org/licenses/MIT).

## Contact Information
If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other information

- 3D visualization using Plotly.js
- Perform mathematical calculations using Math.js
- Color scheme:
 - Mountain Iris: #FF6B6B
 - Color changing iris: #4ECDC4
 - Virginia Iris: #45B7D1
 - Sepal length: #FFA07A
 - Sepal width: #98FB98
 - Petal length: #DDA0DD
 - Petal width: #F0E68C

Note: In order to better display the classification process of the iris data set, the program currently uses randomly generated data points for visualization. In practical applications, real iris flower datasets should be used for more accurate classification display.
