# 🧠 MRI-Visualizer

An interactive tool for visualizing and analyzing Magnetic Resonance Imaging (MRI) data. This project is designed to help researchers, students, and medical professionals explore MRI images efficiently using Python-based tools.

## 📌 Features

- Load and visualize 2D and 3D MRI scans (e.g. `.nii`, `.nii.gz`, or `.dcm` formats)
- Scroll through slices of 3D volumes interactively
- Display anatomical planes: axial, sagittal, and coronal
- Contrast adjustment and basic preprocessing options
- Overlay segmentation masks (if available)

## 🧪 Use Cases

- Educational visualization of brain anatomy
- Basic radiological image inspection
- Preprocessing for deep learning models
- MRI data exploration for biomedical research

## 🛠️ Technologies Used

- Python 3.x
- `nibabel` – for loading NIfTI files
- `matplotlib` / `plotly` – for visualization
- `numpy` / `pandas` – for data handling
- `ipywidgets` – for interactive sliders (in Jupyter)

## 🚀 Getting Started

### 🔧 Installation

git clone https://github.com/yourusername/MRI-Visualizer.git
cd MRI-Visualizer
pip install -r requirements.txt
!git clone https://github.com/yourusername/MRI-Visualizer.git
from visualizer import load_mri, show_slice_viewer

img = load_mri('path/to/your/scan.nii.gz')
show_slice_viewer(img)


MRI-Visualizer/
┣ visualizer.py
┣ example_notebook.ipynb
┣ requirements.txt
┣ README.md
┣ data/
┃ ┗ sample_scan.nii.gz
