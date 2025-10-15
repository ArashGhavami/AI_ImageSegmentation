# Image Segmentation – Phase 1

This project is part of the **Artificial Intelligence** course (Spring 2025) at **Sharif University of Technology**, Computer Engineering Department.  
The goal of this phase is to build and train a **U-Net based image segmentation model** to accurately segment objects from images.

## 📊 Dataset
The dataset used for this project contains pairs of **input images** and **segmentation masks**.  
It is loaded using the [KaggleHub](https://pypi.org/project/kagglehub/) package, which allows easy access to Kaggle datasets directly from the notebook.  

Each image has a corresponding mask that labels object regions at the pixel level.  
The dataset is split into **training** and **validation** sets to evaluate model performance.

## 🧠 Model
The model is based on the **U-Net architecture**, which is well-suited for biomedical and general image segmentation tasks due to its encoder–decoder structure with skip connections.

---

✍️ *Authors*: Shayan Baghayi Nejad & Armin Khosravi  
📅 *Spring 2025*
