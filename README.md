# 🗜️ Accelerating Computer Vision using Model Compression Techniques

This repository contains a collection of Kaggle Notebooks (.ipynb) demonstrating three of the most powerful model compression and optimization techniques in Machine Learning and Deep Learning. These techniques are essential for deploying large models onto resource-constrained edge devices, mobile phones, and web browsers.

## 📂 Repository Structure

The repository is organized into three main directories, each focusing on a specific compression technique:

📦 repository-name

 ┣ 📂 Pruning                 # Notebooks demonstrating filter removal
 
 ┣ 📂 Quantization            # Notebooks demonstrating precision reduction (e.g., FP32 to INT8)
 
 ┗ 📂 Knowledge Distillation  # Notebooks demonstrating Teacher-Student model learning


### 1. ✂️ Pruning

Pruning involves removing redundant or unimportant parameters (weights, neurons, or entire layers) from a trained neural network. This reduces the model size and inference time without significantly impacting the overall accuracy.

### 2. 📉 Quantization

Quantization maps a network's weights and activations from high-precision data types (like 32-bit floating-point) to lower-precision data types (like 8-bit integers). This drastically reduces the memory footprint and accelerates computation.

### 3. 👩‍🏫 Knowledge Distillation

Knowledge Distillation is a technique where a smaller, faster "Student" model is trained to mimic the behavior and generalize the predictions of a larger, more complex "Teacher" model.

---

## 🚀 How to Run the Notebooks

Because these are Jupyter/Kaggle Notebooks, you have several options for running them.

### Option A: Run directly on Kaggle (Recommended for Free GPUs)

Running these on Kaggle is the easiest method since you will have access to their pre-configured environments and free GPU/TPU accelerators.

1. Log in to Kaggle.
2. Click on Create -> New Notebook.
3. In the Notebook editor, click on File -> Import Notebook.
4. Select the GitHub tab, paste the link to the specific .ipynb file from this repository, and click Import.
5. If the notebook requires a specific Kaggle dataset, make sure to add it via the "Add Data" button on the right sidebar.

---

### Option B: Run on Google Colab

You can easily open any notebook from this repository directly in Google Colab.

1. Navigate to Google Colab.
2. Select the GitHub tab in the welcome modal.
3. Paste the URL of this repository.
4. Select the notebook you wish to open.
5. Go to Runtime -> Change runtime type and select GPU if needed.

---

### Option C: Run Locally

If you have a local GPU or want to run the code on your own machine:

#### Clone the repository:
```
git clone https://github.com/rahboddeda/Accelerating-Computer-Vision-using-Model-Compression-Techniques.git
cd Accelerating-Computer-Vision-using-Model-Compression-Techniques
```

#### Set up a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

#### Install dependencies:
```
pip install jupyterlab numpy pandas matplotlib tensorflow torch
```

#### Launch Jupyter:
```
jupyter notebook
```

Then navigate to any notebook and start experimenting.

---

## 🤝 Contributing

Contributions are welcome! If you have a new notebook demonstrating advanced techniques like lottery ticket hypothesis, dynamic quantization, or improved distillation methods, feel free to open a Pull Request.

Steps:
- Fork the repository
- Create a new branch (`git checkout -b feature/AmazingCompression`)
- Commit changes (`git commit -m 'Add feature'`)
- Push (`git push origin feature/AmazingCompression`)
- Open a Pull Request

---

