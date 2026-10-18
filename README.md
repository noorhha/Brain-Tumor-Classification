# Brain Tumor Classification

This project contains a Jupyter/Google Colab notebook for working with a brain tumor image dataset.

## Environment

The notebook is designed to run in **Google Colab** and uses Google Drive to access the project files and dataset.

```python
from google.colab import drive
drive.mount('/content/drive')
```

The project directory used in the notebook is:

```python
PROJECT_DIR = "/content/drive/MyDrive/brain-tumor-project"
```

## Data Folder

The notebook expects the dataset to be available in Google Drive under:

```text
/content/drive/MyDrive/brain-tumor-project/data/brain_tumor
```

The dataset itself is not included in this GitHub repository.

## How to Run

1. Upload the project data to your Google Drive.
2. Open the notebook in Google Colab.
3. Run the Google Drive mounting cell.
4. Make sure the project folder is located at:
   `/content/drive/MyDrive/brain-tumor-project`
5. Run the notebook cells in order.

## Repository Files

```text
Brain-Tumor-Classification/
├── brain_tumor_classification.ipynb
└── .gitignore
```

## Author

Noor Hanna Azzam
