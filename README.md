# Demo Project — Jupyter Notebook Showcase

Welcome to the demo project! This Jupyter Notebook-based demo is designed to showcase key features and capabilities related to computer vision tasks using PyTorch and Meta AI's Segment Anything model.

##  Project Overview

This notebook demonstrates:

* Image processing using OpenCV and NumPy
* Visualization using Matplotlib
* Image segmentation with Meta's **Segment Anything**
* GPU acceleration using **PyTorch + CUDA 11.8**

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/HolubVisionAI/background-swapper
cd background-swapper
```

### 2. Set Up Python Environment

Ensure you are using **Python 3.9+** (recommended). It's best to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

#### PyTorch with CUDA 11.8

```bash
pip install torch==2.0.1+cu118 torchvision==0.15.2+cu118 --index-url https://download.pytorch.org/whl/cu118
```

#### Core Libraries

```bash
pip install opencv-python==4.8.0.76 numpy~=1.26.2 matplotlib==3.7.2
```

#### Segment Anything (Meta AI)

```bash
pip install git+https://github.com/facebookresearch/segment-anything.git
```

Download the SAM model checkpoint:

```bash
wget https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth
```

> Place the downloaded `.pth` file in the project directory or update the model loading path in the notebook accordingly.

#### Jupyter Notebook

```bash
pip install notebook
```

### 4. Launch Notebook

```bash
jupyter notebook
```

Then open the main demo `.ipynb` file in your browser.

---

## Sample Output

Example results and outputs are visualized inside the notebook using `matplotlib`.

---

## License

This demo project uses open-source libraries and research code. Ensure you comply with their respective licenses.


