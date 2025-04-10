# Waste Sorting Project - Environment Setup

This guide provides step-by-step instructions to set up the environment for training the waste classification model.

---

## Download the Dataset 

Google Drive link 🔗 [Dataset](https://drive.google.com/file/d/13V6-HEIAYtSiYbuVxU7qwLlAN8ZLLCKo/view?usp=sharing) \
Extract the folder named "datasets" to the same level as modelT.ipynb\
The Dataset is already preprossed You dont have to Run the preprocessing code again!!.

## 🚀 Step 1: Install Python 3.12.3

First, install **Python 3.12.3** from the official website:  
🔗 [Download Python](https://www.python.org/downloads/release/python-3123/)

After installation, verify the installation by running:

```sh
python --version
```

---

## 🛠 Step 2: Install Miniconda

Download and install **Miniconda** from the official website:  
🔗 [Download Miniconda](https://docs.conda.io/en/latest/miniconda.html)

After installation, verify the installation by running:

```sh
conda --version
```

---

## ⚡ Step 3: Install CUDA & CuDNN (For GPU Acceleration)

Inside **Conda Command Prompt**, run:

```sh
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
```

This installs **CUDA 11.2** and **cuDNN 8.1.0**, which are required for TensorFlow GPU support.

---

## 📂 Step 4: Create Conda Environment

Navigate to your **project folder** and create a new folder named **`envs`** inside it.  

Then, create a **Conda environment**:

```sh
conda create --name waste_sorting python=3.9 -y
```

Activate the environment:

```sh
conda activate waste_sorting
```

---

## 🔧 Step 5: Install TensorFlow

Install **TensorFlow 2.10** (latest version that supports GPU acceleration):

```sh
python -m pip install "tensorflow<2.11"
```

Verify if GPU is being used:

```sh
python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
```

---

## 📦 Step 6: Install Required Libraries

Install all necessary libraries:

```sh
pip install numpy==1.23.5
pip install matplotlib
pip install keras-efficientnet
pip install keras opencv-python pandas scikit-learn tqdm pillow
```

---

## 🔍 Step 7: Verify Installed Packages

To list all installed packages inside the Conda environment:

```sh
conda list
```

This should display all the installed dependencies.

---

## ✅ Environment Setup Complete!

You are now ready to proceed with the project. 🚀
