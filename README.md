# Recipe Image Generator

## Overview

The Recipe Image Generator is a web application that utilizes the OpenAI API, Langchain.js, and Replicate to create new images based on user input. Users can input recipe names, and the AI will render an image that visually represents the input recipe. This README.md file provides an overview of the project, installation instructions, and usage guidelines.

## Features

- **Recipe Image Generation**: Users can input recipe names, and the application will generate images that symbolize the provided recipes.
- **OpenAI Integration**: The application leverages the OpenAI API to generate creative and relevant images.
- **Langchain.js**: Langchain.js is used for natural language processing and understanding user input.
- **Replicate**: Replicate is used for managing and storing generated images.
- **Convex Backend**: Convex is used for backend calculations, ensuring efficient and accurate processing of user requests.

## Installation

To set up the Recipe Image Generator, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/recipe-image-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd recipe-image-generator
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Configure the environment variables:

   Create a `.env` file in the root directory of the project and add the following variables:

   ```dotenv
   OPENAI_API_KEY=your_openai_api_key
   REPLICATE_API_KEY=your_replicate_api_key
   ```

   Replace `your_openai_api_key` and `your_replicate_api_key` with your actual API keys.

5. Start the application:

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000`.

## Usage

1. Access the Recipe Image Generator web application in your browser by navigating to `http://localhost:3000` (or the appropriate URL where you deployed the application).

2. On the home page, you will see a text input field where you can enter the name of the recipe you'd like to generate an image for.

3. After entering the recipe name, click the "Generate Image" button.

4. The application will send the input to the Langchain.js for natural language processing, then use the OpenAI API to generate an image based on the recipe name.

5. Once the image is generated, it will be displayed on the screen, and a download link will be provided to save the image to your device.

6. You can continue generating images for different recipe names by repeating the process.

## Credits

- This project makes use of the [OpenAI API](https://openai.com) for image generation.
- [Langchain.js](https://langchainjs.com) is used for natural language processing.
- [Replicate](https://replicate.ai) is used for image management and storage.
- The backend calculations are powered by [Convex](https://convex.dev).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Enjoy using the Recipe Image Generator!

