# Brain-Tumor-Detection

## Dataset

The dataset we use here is provided by Kaggle. The dataset contains **7023** images of human brain MRI classified into 4 classes (meningioma, glioma, pituitary tumor and no tumor). The dataset is available at <https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection>. The size of the images in this dataset is different, so we need to resize the images to a fixed size.

For the dataset, please place the dataset in a folder in the root called `Dataset`. The folder structure should be as follows:

``` tree
├── Dataset
│   ├── Testing
│   ├── Training
├── main.ipynb
├── README.md
└── .gitignore
```
