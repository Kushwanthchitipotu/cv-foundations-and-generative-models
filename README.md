# Computer Vision Assignments — Foundations to Generative Models

This repository contains my course assignments for Computer Vision, covering both **traditional image processing techniques** and **deep generative models**.  
It demonstrates my understanding of the entire spectrum of CV — from low-level pixel operations to advanced neural network architectures like VAE and GAN.

---

##  Repository Structure

```
Computer-Vision-Assignments/
│
├── 01_Point_Operations_and_Edge_Detection/
│ ├── operations.ipynb
│ ├── README.md
│ ├── requirements.txt
│ └── sample_outputs/
│
├── 02_VAE/
│ ├── ai22btech11006_hw2.ipynb
│ ├── README.md
│ ├── requirements.txt
│ └── generated_samples/
│
├── 03_GAN/
│ ├── ai22btech11006_hw3.ipynb
│ ├── README.md
│ ├── requirements.txt
│ └── generated_samples/
│
└── README.md
```


---

##  Assignments Overview

### 1. Point Operations & Edge Detection
- Covers intensity transformations, histogram equalization, and convolution-based edge detection.
- Implemented in Python with OpenCV & NumPy.

### 2. Variational Autoencoder (VAE)
- Implements a VAE from scratch using PyTorch.
- Trained on image datasets to generate new samples from latent space.

### 3. Generative Adversarial Network (GAN)
- Implements a GAN from scratch using PyTorch.
- Demonstrates adversarial training between generator and discriminator.

---

##  Tech Stack
- **Languages:** Python
- **Libraries:** NumPy, OpenCV, Matplotlib, PyTorch
- **Tools:** Jupyter Notebook

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/computer-vision-assignments.git
   cd computer-vision-assignments
  ```
2. Go into the desired assignment folder:
  ```bash
  cd VAE
  ```
3.  Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
4. open the notebook:
  ```bash
    jupyter notebook VAE.ipynb
  ```

## Notes
- All notebooks are runnable in Google Colab without modification.
- Output images are stored in respective folders (sample_outputs/, generated_samples/).
- The repo demonstrates progression from traditional CV algorithms to deep learning models.

## Credits
This work was completed as part of the AI3005 — Computer Vision course at IIT Hyderabad.
I would like to thank Prof. Sumohana Channappayya for guidance and valuable feedback throughout these assignments.
