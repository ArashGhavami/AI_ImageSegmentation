# Introduction

<br>
<font>
<div dir=ltr>
<img src="https://cdn.freebiesupply.com/logos/large/2x/sharif-logo-png-transparent.png" width=150 height=150>
<div dir=ltr align=center>
<font color=0F5298 size=7>
    Artificial Intelligence <br>
<font color=2565AE size=5>
    Computer Engineering Department <br>
    Spring 2025<br>
<font color=3C99D size=5>
    Project-Phase1<br>
    Image Segmentation<br>
<font color=696880 size=4>
    Shayan Baghayi Nejad-Armin Khosravi

> Language: **python** · Version: **3.12.1** · Kernel: **Python (notebook-venv)**


## Overview
<br>
<font>
<div dir=ltr align=center>
<img src="https://cdn.freebiesupply.com/logos/large/2x/sharif-logo-png-transparent.png" width=150 height=150>
<div dir=ltr align=center>
<font color=0F5298 size=7>
    Artificial Intelligence <br>
<font color=2565AE size=5>
    Computer Engineering Department <br>
    Spring 2025<br>
<font color=3C99D size=5>
    Project-Phase1<br>
    Image Segmentation<br>
<font color=696880 size=4>

## Requirements
The notebook uses the following Python packages (inferred from imports):

- `torch`
- `os`
- `shutil`
- `numpy`
- `PIL`
- `kagglehub`
- `matplotlib`
- `torchvision`
- `tqdm`

> Tip: create a virtual environment to keep dependencies isolated.

## Setup
```bash
# 1) Create a virtual environment
python -m venv .venv
# 2) Activate it (Linux/Mac)
source .venv/bin/activate
#    or on Windows
# .venv\Scripts\activate
# 3) Install dependencies (edit as needed)
pip install -U pip
pip install PIL kagglehub matplotlib numpy os shutil torch torchvision tqdm
```

## Data
The notebook does not reference any explicit external data files (or they could not be inferred).



## How to Run
1. Open the notebook:
   - From terminal: `jupyter lab` or `jupyter notebook`
   - Or open in VS Code / JupyterLab.
2. Run cells **top-to-bottom** (Kernel → Restart & Run All) for a clean run.
3. If paths are relative, place data files in the same directory as the notebook or adjust the paths in the code.

## Notebook Structure
The following sections were detected from markdown headings:

- Introduction
    - Environment Setup
    - Hyperparameter Setting
- Data Preparation
    - Loading Images
    - Data Visualization
    - Dataset Creation
- UNet
    - Convolution Block
    - Up Convoluitional Block
    - Complete UNet Structure
- Attention UNet
    - Attention Mechanism
- Residual Attention UNet
- Training
    - Loss Function
    - Training Epoch
- Model Training
    - UNet
    - Prediction Visualisation

## Functions & Classes
**Functions**:
- `__getitem__()`
- `__init__()`
- `__len__()`
- `_pad_to_match()`
- `evaluate_model()`
- `forward()`
- `load_images_and_masks()`
- `plot_training_curves()`
- `to_display_image()`
- `train_one_epoch()`
- `visualize_image_mask_prediction()`
- `visualize_images_and_masks()`

**Classes**:
- `AttentionBlock`
- `AttentionUNet`
- `ConvBlock`
- `DiceLoss`
- `IouLoss`
- `OverallLoss`
- `ResidualAttentionUNet`
- `ResidualConvBlock`
- `RoadDataset`
- `UNet`
- `UpConvBlock`

## Results / Outputs
No explicit file outputs detected.



## Reproducibility
- Use a **clean kernel** and set a random seed where applicable (e.g., `numpy.random.seed(42)`).
- Consider exporting an **environment file**:
  ```bash
  pip freeze > requirements.txt
  ```
- For long runs, prefer `Restart & Run All` to ensure order independence.

## License
Specify your license here (e.g., MIT). If omitted, assume **All Rights Reserved**.
