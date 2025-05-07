# Text-to-Image-Generator-with-Stable-Diffusion
Colab link - https://colab.research.google.com/drive/1fhWAp1fd1QEddFpR-C6rL5SHDC02VL3Z#scrollTo=w_J8ihW4C4g3
![image](https://github.com/user-attachments/assets/104afbc3-58a3-4dc1-8d29-07873d186230)
This project showcases a complete pipeline for generating high-quality images from natural language prompts using the Stable Diffusion v1.5 model via Hugging Face’s Diffusers library. It also features an interactive Gradio-based web interface for user-friendly image generation.
💡 Key Highlights

## 🔗 Integration with Hugging Face Diffusers
Utilizes the powerful and easy-to-use diffusers library for accessing and operating the pretrained Stable Diffusion v1.5 model (runwayml/stable-diffusion-v1-5).

## 🧠 Model & Pipeline Setup
Employs the DPMSolverMultistepScheduler for faster inference. The model pipeline is optimized for both CUDA and CPU, with attention slicing enabled for memory efficiency on GPU.

## 🧪 Parameter Control
Users can experiment with a wide range of parameters to refine the generation output:

Prompt & Negative Prompt: Guide image content and suppress undesired elements.

Image Size (width × height): Custom resolution up to 1024×1024.

num_inference_steps: Adjust denoising iterations for quality vs speed.

guidance_scale: Controls adherence to the prompt vs creative freedom.

Seed Control: Enables reproducibility or randomization.

## 🖼️ Gradio Interface
A clean and responsive UI built with Gradio lets users generate and view images by simply entering prompts. Example prompts are provided for quick testing.

## 📁 Modular & Readable Code
The project is written in Python with class-based architecture (TextToImageGenerator) for clarity, reusability, and scalability. Includes functions for generation and saving outputs.

## 📌 Sample Notebook & Output Images
You can test the code and view output images directly in this Colab notebook:

## 🔗 Link: [Colab link](https://colab.research.google.com/drive/1fhWAp1fd1QEddFpR-C6rL5SHDC02VL3Z#scrollTo=w_J8ihW4C4g3)

## 🚀 Technologies Used

Python 3.10+

Hugging Face Diffusers

PyTorch

Gradio

PIL (Pillow)

NumPy

## 🔧 How to Run

Install dependencies via pip:
pip install torch diffusers gradio pillow numpy

Run the main Gradio app to start generating images:
Text to image .ipynb
