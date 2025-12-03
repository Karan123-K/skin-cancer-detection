# skin-cancer-detection
An AI-powered medical imaging project that classifies skin lesions as Benign or Malignant. with accuracy of 92%


Title: Skin Cancer Detection using DINOv2
Short Description: An AI-powered medical imaging project that classifies skin lesions as Benign or Malignant with high accuracy (~98% AUC). This system leverages Transfer Learning using the self-supervised DINOv2 Vision Transformer (facebook/dinov2-base) trained on a balanced dataset of 10,000 dermoscopic images. The project includes a complete training pipeline in PyTorch and a user-friendly web interface built with Flask for real-time predictions.

Key Features:

Model: Fine-tuned DINOv2 (Vision Transformer) with a custom classification head.

Dataset: 10,000 images (50/50 Benign/Malignant split).

Tech Stack: PyTorch, Transformers, Flask, HTML/CSS.

Performance: Achieved an AUC score of 0.9778.

Deployment: Includes a Flask web app for easy model inference.

How to Run:

Install dependencies: pip install torch torchvision transformers flask pillow

Run the web app: python app.py

Access via browser at http://127.0.0.1:5000
