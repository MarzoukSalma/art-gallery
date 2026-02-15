
# 🎨 Art Gallery – Interactive Generative Art Project

## 1. Project Description

**Art Gallery** is an academic Python project that combines:
- Generative Art
- Data Visualization
- Image & Audio Manipulation
- Interactivity
- Web Integration with Flask
- Machine Learning features

The project allows users to generate, visualize, modify, and interact with artworks through a web interface.

---

## 2. Academic Requirements Covered

### ✔ Generative Art
- Python + Object-Oriented Programming
- Use of loops and conditionals
- Interactive drawing and artwork generation

### ✔ Data-Driven Visualization
- Pandas + Matplotlib
- Artistic visual representations of data

### ✔ Image & Audio Manipulation
- Image processing with OpenCV & Pillow
- Audio effects with PyDub

### ✔ Interactivity
- User interaction through Flask
- Artwork gallery navigation

### ✔ Web Integration
- Flask backend
- Jinja2 templates
- Dynamic routes and rendering

### ✔ Machine Learning features
- Machine Learning (PyTorch, Transformers)
- Image caption generation
- Style transfer (can be disabled if needed)

---

## 3. Project Structure

```

art-gallery/
│
├── app.py
├── requirements.txt
├── drawing_tool.py
├── visualization.py
├── image_effects.py
├── audio_processor.py
├── generate_descriptions.py
├── style_transfer.py
│
├── templates/
├── static/
├── gallery/
└── fast-neural-style/  

````

---

## 4. Setup Instructions (All Steps)

### Step 1 – Clone the Repository
```bash
git clone https://github.com/MarzoukSalma/art-gallery.git
cd art-gallery
````

---

### Step 2 – Create Virtual Environment

python -m venv venv
```

Activate it:

-Windows:

venv\Scripts\activate


 -Linux / macOS

source venv/bin/activat

---

### Step 3 – Install Dependencies


pip install --upgrade pip
pip install -r requirements.txt


⚠️ Note:

* Some ML libraries are heavy (PyTorch, Transformers).
* If disk space is limited, ML features can be disabled without affecting core functionality.

---

### Step 4 – Run the Application


python app.py


Open in browser:


http://127.0.0.1:5000


---


## 6. Known Issues & Solutions

### Style Transfer / Torch Errors

If PyTorch causes errors:

* Comment or disable `style_transfer.py`
* The project remains fully functional without it

### Audio Issues

* `simpleaudio` may fail on Windows
* Audio features can still work via PyDub


---

## 8. Author

Salma Marzouk
Academic Project – Interactive Generative Art
Python · Flask · Creative Coding · AI
---


