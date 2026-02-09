# 🎨 Art Gallery – Interactive Generative Art Platform

## 📌 Project Overview

**Art Gallery** is an academic project that combines **generative art**, **data visualization**, **image/audio manipulation**, and **web interactivity** into a single interactive platform.

The project is implemented in **Python** and delivered as a **Flask web application**, allowing users to explore, generate, transform, and interact with digital artworks in real time.

This project follows an **object-oriented programming (OOP)** approach and integrates multiple Python libraries commonly used in creative coding and data science.

---

## 🎯 Academic Objectives

This project fulfills the following academic requirements:

### 1. Generative Art
- Creation of **multiple unique generative artworks**
- Use of:
  - Python
  - Object-Oriented Programming (OOP)
  - Loops and conditionals
- Interactive features such as:
  - Drawing tools
  - Color selection
  - User-controlled parameters

### 2. Data-Driven Visualization
- Use of **real or simulated datasets**
- Artistic visualizations using:
  - Pandas
  - Matplotlib
- Visual outputs such as:
  - Abstract charts
  - Stylized graphs

### 3. Image & Audio Manipulation
- Image processing using:
  - OpenCV
  - Pillow (PIL)
- Audio processing using:
  - PyDub
- Features include:
  - Image filters and effects
  - Audio transformations (speed, effects, layering)

### 4. Interactivity
- User interaction through:
  - Flask web interface
  - Pygame-based tools
- Gallery navigation with:
  - Artwork previews
  - Image saving and browsing

### 5. Web Integration
- Flask web application
- Jinja2 templating
- Dynamic routes for:
  - Uploading images
  - Generating artworks
  - Displaying results

### 6. Bonus – Machine Learning 
- AI-based features such as:
  - Image caption generation
  - Artistic transformations
- Integration of:
  - PyTorch
  - Transformers / Hugging Face models
- Optional neural style transfer module

---

## 🗂 Project Structure
art-gallery/

│
├── app.py # Main Flask application

├── requirements.txt # Python dependencies

│
├── templates/ # HTML templates (Jinja2)
│ ├── index.html
│ ├── gallery.html
│
├── static/
│ ├── css/
│ ├── gallery/ # Generated artworks
│
├── gallery/ # Saved images
│
├── drawing_tool.py # Generative drawing logic (OOP)
├── visualization.py # Data visualization module
├── image_effects.py # Image processing functions
├── audio_processor.py # Audio manipulation module
├── generate_descriptions.py # AI-based text/image descriptions
├── style_transfer.py # Neural style transfer 
│
└── fast-neural-style/ # External ML module 


---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/MarzoukSalma/art-gallery.git
cd art-gallery

