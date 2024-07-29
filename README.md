# Text-to-Image-Generator

MoniGeneratesImage is a simple web application that generates images based on textual descriptions using the Hugging Face API.

Features
Input field for entering image descriptions.
Generate button to trigger image generation.
Display of the generated image.

Structure
HTML
The index.html file contains the structure of the web application. It includes:

A heading with the title "Monisha Generates Image".
An input field for the user to enter their image description.
A button to trigger the image generation process.
An image element to display the generated image.
CSS
The style.css file defines the styles for the web application, including:

Background color and font settings.
Styles for the input field and image element.
Custom styles for the button with glowing animation.
JavaScript
The script.js file contains the logic for fetching the generated image from the Hugging Face API. It includes:

An authorization token for accessing the Hugging Face API.
Event listener for the button to trigger the image generation process.
Function to send a request to the API and display the generated image.

ote
Ensure that you have an active internet connection to fetch the images from the API.
Replace the placeholder token with your own Hugging Face API token if needed.
