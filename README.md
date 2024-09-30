## Lunar-Image-Processing-Project
This project processes lunar images with advanced techniques, including noise reduction, enhancement, and the detection of Permanently Shadowed Regions (PSR). The application features a Graphical User Interface (GUI) for easy use, powered by PyQt5, and it allows for both image processing and metadata handling.
# Features
Preprocessing: Noise reduction, contrast adjustment, and image cropping.
Denoising: Advanced noise reduction techniques such as BM3D.
PSR Mapping: Detects and highlights PSR regions on lunar images.
Enhancement: Further improves the quality of lunar images after PSR detection.
Metadata Export: Automatically extracts and exports metadata, including file details and processing results.
SNR Analysis: Compares processed images with original ones to analyze improvements in image quality, particularly in PSR regions.
# Project Workflow
Landing Page (landing_page.py)
Displays project information and buttons to start the main application or exit.

Main GUI (gui.py)
Allows users to upload lunar images and perform processing tasks, including preprocessing, PSR mapping, and enhancement.

Preprocessing (preprocessing.py)
Processes images by reducing noise, adjusting contrast, cropping, and extracting metadata.

Advanced Denoising (advanced_denoising.py)
Reduces noise further using the BM3D algorithm after preprocessing.

PSR Mapping (psr_mapping.py)
Detects Permanently Shadowed Regions on the moon and overlays them on the image.

Image Analysis (analysis.py)
Extracts features from images and computes metrics such as Signal-to-Noise Ratio (SNR) and other image comparison techniques.

Image Enhancement (enhancement.py)
Applies further enhancements to images after PSR detection and analysis.

Metadata Handling (metadata_handling.py)
Extracts metadata from image files and saves them to a JSON file.

Export Handling (export_handling.py)
Provides functionality for exporting processed images and their corresponding metadata.

# Installation
Clone the repository:

git clone https://github.com/your-username/lunar-image-processing.git
cd lunar-image-processing
Install the required dependencies:

pip install -r requirements.txt
Run the application:

python src/landing_page.py
# Requirements
Python 3.x
PyQt5
OpenCV
NumPy
Scikit-image
BM3D library
# Usage
Start the GUI: The application opens with a landing page (landing_page.py), where you can proceed to the main interface.
Upload Lunar Image: Use the upload button to select a lunar image for processing.
Process the Image: Choose various options like preprocessing, denoising, and PSR mapping from the GUI.
Analyze and Export: The application provides options for SNR analysis and exporting both the processed image and its metadata.
# Project Files
landing_page.py: The initial entry point for the project.
gui.py: Main interface for image uploading and processing.
preprocessing.py: Handles image preprocessing tasks.
advanced_denoising.py: Performs denoising using advanced methods.
psr_mapping.py: Detects PSR regions on the lunar surface.
analysis.py: Analyzes processed images, including SNR calculation.
enhancement.py: Further image enhancement features.
metadata_handling.py: Extracts and exports metadata.
export_handling.py: Manages exporting processed images and metadata.
# Future Enhancements
Deep Learning Integration: Train custom models for more sophisticated denoising and PSR detection.
Real-Time Processing: Enable real-time lunar image processing using a more optimized approach.
Interactive GIS Features: Integrate GIS functionalities for advanced lunar surface analysis.
Additional Image Formats: Support for more image formats beyond the current ones.
# License
This project is licensed under the MIT License - see the LICENSE file for details.
