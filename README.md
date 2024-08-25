### Image Generator Website
Welcome to the Image Generator Website, a powerful tool that allows users to generate images based on text prompts. This website is powered by an API and is deployed on Netlify.
 
## Live Demo
Check out the live version of the website: [Image Generator Website](https://image-gen-web.netlify.app/)

## Features
* Text Prompt-Based Image Generation: Simply input your desired text prompt, and the API will generate a corresponding image.
* Multiple Image Options: Choose between different styles and dimensions (square, tall, wide).
* Safety Settings: Toggle safety options on or off to control the content of the generated images.
* Fast and Reliable: Deployed on Netlify for quick access and optimal performance.

## API Details
The image generation is powered by a my API:
# Endpoint: `https://death-image.ashlynn.workers.dev/`
# Parameters:
  prompt: The text input that describes the image you want to generate.
  image: Number of images to generate (e.g., 3).
  dimensions: Image dimensions (options: square, tall, wide).
  safety: Safety mode (options: false for unsafe content, true for safe content).

## Example API Call 

```json
{https://death-image.ashlynn.workers.dev/?prompt=Your+Text+Here&image=3&dimensions=square&tall&wide&safety=true
}
