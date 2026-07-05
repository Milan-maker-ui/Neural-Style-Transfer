# Neural Style Transfer using TensorFlow 

This project implements **Neural Style Transfer (NST)** using **TensorFlow** and the **VGG19** pre-trained convolutional neural network.

Neural Style Transfer is a deep learning technique that combines:
- **Content** from one image
- **Artistic style** from another image

to generate a new image that preserves the content while adopting the artistic appearance of the style image.

---

## Features

- Load custom content and style images
- Uses pre-trained VGG19 model
- Extracts content and style features
- Computes content loss and style loss
- Optimizes the generated image using Gradient Descent
- Displays the stylized output image

---

## Technologies Used

- Python
- TensorFlow 2.x
- NumPy
- Matplotlib
- VGG19 (Pre-trained CNN)

---

## Working

1. Load content image.
2. Load style image.
3. Preprocess images.
4. Load the pre-trained VGG19 network.
5. Extract content and style features.
6. Calculate:
   - Content Loss
   - Style Loss
   - Total Loss
7. Optimize the generated image.
8. Display the final stylized image.

---

## Results

The generated image preserves the structure of the content image while adopting the colors, textures, and artistic patterns from the style image.

---

## Applications

- Digital Art
- Image Editing
- AI-based Painting
- Creative Design
- Graphic Design
- Mobile Photo Filters

---

## Future Improvements

- Faster Style Transfer using Feed Forward Networks
- Multiple Style Blending
- Real-time Style Transfer
- Video Style Transfer
- Web Deployment using Flask or Streamlit

---

## Requirements

- Python 3.10+
- TensorFlow
- NumPy
- Matplotlib
  
---

This project is intended for educational and learning purposes.
