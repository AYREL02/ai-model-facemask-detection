# AI Face Mask Detection System Model

A structured pipeline for real-time mask classification using **PyTorch** and **ResNet18** transfer learning.

## Project Structure

- **`data/`**: Source data and images used for training and testing.
- **`models/`**: Trained weights in **PyTorch (.pth)** format.
- **`notebook/`**:
    - `01_Exploration.ipynb`: Data analysis, visualization, and dataset preparation.
    - `02_Training.ipynb`: Model architecture, training, and checkpointing.
    - `03_Testing.ipynb`: Real-time inference and UI visualization.
- **`requirements.txt`**: List of Python dependencies for the environment.

## Workflow (Visual Studio Code)

1. **Environment Setup**: Install dependencies using `pip install -r requirements.txt`.
2. **Data Prep**: Use `01_Exploration.ipynb` to analyze the mask dataset and prepare images.
3. **Train Model**: Run `02_Training.ipynb` to train the ResNet18 model and export to `models/`.
4. **Run Inference**: Execute `03_Testing.ipynb` for real-time detection and visual output.

## Tech Stack
* **Python** (VS Code / Jupyter)
* **PyTorch** (Model architecture and training)
* **OpenCV** (Real-time video processing)
* **Matplotlib & Pillow** (Image processing and visualization)

---
*Private Development Repository - [AYREL02](https://github.com/AYREL02)*
