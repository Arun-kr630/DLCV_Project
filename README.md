---
 
## 💾 Dataset
 
Download and unzip the following datasets into the `dataset/` directory:
 
1. [Real and Fake Images Dataset for Image Forensics](https://www.kaggle.com/datasets/shivamardeshna/real-and-fake-images-dataset-for-image-forensics)
2. [DeepFake and Real Images Dataset](https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images)
 
> ⚠️ **Important**: Ensure the folder structure follows exactly this format:
 
```
dataset/
├── Data Set 1/
│   ├── train/
│   │   ├── real/
│   │   └── fake/
│   ├── validation/
│   │   ├── real/
│   │   └── fake/
│   └── test/
│       ├── real/
│       └── fake/
├── Data Set 2/
├── Data Set 3/
└── ...
```
 When dataset is downloaded the folder sturcture would be not according to above structure.
❌ Do **not** include extra nested directories like `dataset/DataSet1/DataSet1/` — this will cause **Assertion error: datasets should not be an empty iterable**.
 
---
Real & Fake Images Dataset-For image forensics | Kaggle
A comprehensive dataset for image forensics, enabling the detection and analysis

⚠️ **Important**: Adjust cuda device according to yourself.


This repo consist three different python notebook
1 - AutoEncoder - This notebook contain the code and result of experiment with vanilla autoencoder and supervised AutoEncoder
2 - Resnet_experiment - contain the code and result of experiment with resnet model
3 - multiple_model_experiment - contain the code and result of experiment with multiple CNN model


Python packages 
1. torch
2. torchvision
3. kaggle
4. numpy
5. matplotlib
6. image
7. sk-learn
8. glob
9. pandas
10. tqdm
11.  
