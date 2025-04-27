# NN-Tumor-Classification

Authors: Rhea Sridhar & Yashwanth Alluri <br> 
Repository: NN-Tumor_Classification <br> 
Objective: Build an automated system to classify MRI scans as "tumor" or "no tumor" using deep neural networks (CNNs). <br> 

## Project Overview
Brain tumor detection from MRI scans is critical for early intervention and treatment planning.
Manual evaluation by radiologists is slow and can introduce diagnostic errors.
This project uses Convolutional Neural Networks (CNNs) to automate MRI classification, aiming to assist healthcare professionals with faster, more accurate diagnostic support.

We implemented and compared multiple CNN architectures across different public MRI datasets to assess the impact of dataset size, architecture complexity, and training strategy on classification performance.

## Project Structure
```
NN-Tumor_Classification/
│
├── MLProject/                       # Main project folder
│   ├── cancerIA-dataset/             # Dataset 1 (Cancer Imaging Archive)
│   │   ├── yes/                      # MRI images with tumors
│   │   └── no/                       # MRI images without tumors
│   │
│   ├── dataport-dataset/             # Dataset 2 (IEEE Dataport)
│   │   ├── yes/
│   │   └── no/
│   │
│   ├── figshare-dataset/             # Dataset 3 (Figshare)
│   │   ├── yes/
│   │   └── no/
│   │
│   ├── MRI-CNN-cancerIA-dataset.ipynb    # Notebook for CancerIA dataset
│   ├── MRI-CNN-dataport-dataset.ipynb    # Notebook for Dataport dataset
│   └── MRI-CNN-figshare-dataset.ipynb    # Notebook for Figshare dataset
│
└── README.md                       # Project documentation
```

## How to Run the Project
1. Clone the repository:
 ```
  git clone https://github.com/yourusername/NN-Tumor_Classification.git
```
```
  cd NN-Tumor_Classification
```

2. Install Dependencies
```
  pip install tensorflow keras numpy pandas matplotlib scikit-learn opencv-python tqdm
```
3. Run the Notebooks
  
  Each of the notebooks runs the same code, but on different datasets. To train and test the models, open one of the following notebooks:

  For the CancerIA dataset: MRI-CNN-cancerIA-dataset.ipynb <br> 
  For the Dataport dataset: MRI-CNN-dataport-dataset.ipynb <br> 
  For the Figshare dataset: MRI-CNN-figshare-dataset.ipynb <br> 



