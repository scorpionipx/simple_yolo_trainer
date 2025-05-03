# simple_yolo_trainer
A lightweight, beginner-friendly toolkit for training YOLO object detection/segmentation models with minimal setup and clear instructions. Ideal for custom datasets and rapid experimentation.

⚙️ Prerequisites
Before you begin, make sure your system meets the following requirements:

Operating System: Windows (tested on Windows 11)

Python: 3.8 or higher (tested on 3.9.13)

NVIDIA GPU (Recommended):
  - Required for training with CUDA acceleration
  - Ensure NVIDIA drivers, CUDA Toolkit, and cuDNN are properly installed

pip: Python package installer

Git: For cloning the repository

💡 Note: Training without a GPU is possible but significantly slower and not recommended for large datasets or models.


## 📦 Installation

Follow the steps below to set up your environment and get started:

### 1. Clone the repository

```bash
git clone https://github.com/scorpionipx/simple_yolo_trainer
cd simple_yolo_trainer
```


### 2. Create a virtual environment

```bash
python -m venv .venv
```
OR (you might need to install virtualenv first into your Python distribution)
```bash
python -m virtualenv .venv
```

### 3. Activate the environment

```cmd
.\venv\Scripts\activate
```
