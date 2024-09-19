# DALL-E Image Generation 
Applied knowledge in working with DALL-E, a state-of-the-art image generation model, 
and built an image generation tool to explore and
demonstrate expertise in advanced AI technologies.
->Used Replit to code

# Project Overview:

The "Custom Image Generator" is a web application that uses OpenAI's DALL-E 3 model to create images based on user-provided textual descriptions. This project combines Flask for the backend with HTML, CSS, and JavaScript for the front end.

# Key Components:

Backend Functionality:

Flask Web Framework: Manages HTTP requests and routes.
OpenAI Integration: Uses OpenAI's DALL-E 3 model to generate images from text descriptions. The API key is managed via environment variables for security.
Image Generation: The generate_tutorial function sends a textual description to the DALL-E 3 model and retrieves the image URL.
Front-End Features:

HTML Form: Users input a description of the image they want to generate.
Bootstrap: Provides styling for a clean and responsive user interface.
JavaScript Functions:
generateTutorial: Sends the description to the server, retrieves the image URL, and displays the image on the webpage.
copyToClipboard: Copies the image URL to the clipboard for easy sharing.
Routes and Functions:

/ (Home Route): Displays the HTML form for user input. Handles form submissions and displays the generated image.
/generate (Image Generation Route): Processes the user input, calls the generate_tutorial function, and returns the image URL.
Deployment:

The application runs on 0.0.0.0 and port 8080, making it accessible from any IP address on port 8080.
How It Works:

User Input: Users enter a description of the desired image into the form.
Image Generation: Upon form submission, the generateTutorial function sends the description to the backend.
OpenAI API: The backend uses OpenAI's DALL-E 3 model to generate an image based on the provided description and retrieves the image URL.
Output Display: The image is displayed on the web page, and users can copy the image URL to their clipboard.
