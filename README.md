# Image Captioning With Gradio
This project demonstrates how to create a web application that generates captions for images using the BLIP-2 model and the Gradio library. Follow the steps below to set up and run the application.

## Table of Contents
   * Introduction
   * Setup Instructions
   * Usage
   * Code Explaination
   * Contribution
   * License
   * Contact

## Introduction
In this project, I will explain the steps I used to create a web application that generates captions for images using the BLIP-2 model and the Gradio library. The application leverages a pretrained model from Salesforce for generating descriptive captions.

## Setup Instructions
### Prerequisites
  Ensure you have the following:
   * Python 3.x
   * Pip (Pythhon package Installer)
     
### Installation
1. Clone the repository
2. Install the require libraries:
   - pip install gradio transformers pillow
   - pip install tensorflow
   - pip install pytorch

## Create the Python Script
create a new Python file name 'image_captioning_app.py' and add the codes

## Running the Application
To run the application, navigate to the directory conntaining 'image_captioning_app.py' and execute the following command:
<img width="410" alt="Screenshot 2024-07-25 183015" src="https://github.com/user-attachments/assets/8f61043e-ae3c-4a29-81b4-5794b877e768">
This will start a local web server. Open the provided URL in yout web browser to use the image captioning app.

## Usage
1. Open your browser and navigate to the local server URL provided in the terminal
2. Upload an image using the web interface
3. Wait for the model to process the image and generate a caption
4. The generated caption will be displayed on the web page.

## Code Explaination
### imports
- **'gradio'** for building the web interface.
- **'numpy'** for handling image arrays.
- **'PIL'** 'S **'Image'** for image processing.
- **'AutoProcessor'** and **'BlipForConditionalGeneration'** from **'transformers'** for loading the model and processor.

## Model and Processor Intialization
  The pretrained processor and model are loaded using the **'AutoProcessor'** and **'BlipForConditionalGeneration'** from the Salesforce model.

## Caption Generation Function
  - **Input Conversion**: Converts the input image (numpy array) to a PIL Image and converts it to RGB format.
  - **Processing**: Prepares the image for the model.
  - **Caption Generation**: Generates a caption using the model
  - **Decoding**: Converts the generated tokens to readable text
 
## Gradio Interface
Sets up Gradio interface for the **'caption_image'** function, specifying the input types as an image and the output type as text. It also provides a title and description for the web app.

## Contributing
Contributions are wellcome! Please fork this reporitory and submit a pull request for any enhancement or bug fixes with explaination.

## Contact
For any questions or inquiries, please coontact:
- Name: **Bakary Gibba**
- Email: bakarygibba055@gmail.com
- Linkedln: https://www.linkedin.com/in/bakary-gibba-6409bb248?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app


## The System Interface:
<img width="952" alt="Gradio Inerface 2" src="https://github.com/user-attachments/assets/206304ed-cd26-42f9-ba6f-e5fa1404ce6c">


## The Interface where the image is been uploaded:

<img width="959" alt="My Gradio Outcome" src="https://github.com/user-attachments/assets/376693af-395e-49ea-9089-46af0fb12c85">



