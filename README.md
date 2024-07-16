# Cervical Cancer - Cytology Project

This project showcases an example of using a Convolutional Neural Network (CNN) to perform multi-class classification on images of isolated cervical cells. The goal is to demonstrate a simple yet effective CNN model built with Keras, utilizing the Kaggle dataset containing manually cropped images of cervical cytology screenings.

![image](https://github.com/user-attachments/assets/025eec6b-d20f-4533-be17-12fda1680af5)


## Files
- **Cervical_Cancer_Project.ipynb**: The Jupyter Notebook that contains the code for the image classification model.

## Directory Structure
- **api**: Contains the FastAPI application (located in `api/main.py`). Please note that this is still a work in progress.
- **cropped_images**: Directory for storing the images used in the project. These images are not included in the GitHub repository due to their size.
- **models**: Stores different versions of the models. Only the latest version is kept here to manage repository size.
- **saved_models**: Similar to the `models` directory, it contains the different versions of the models, with only the latest version saved.
- **notebook**: Contains the Jupyter notebook `Cytology_Project.ipynb`. This notebook includes comments and explanations that guides the user through the entire process, including:
  - Image extraction
  - Train/validation/test split
  - Preprocessing with data augmentation
  - CNN model training, testing and saving

## Dataset
The dataset used in this project is the SipakMed dataset, which contains images of isolated cells that have been manually cropped. The dataset is available on Kaggle and can be accessed via the following link:
[Kaggle Dataset - Cervical Cancer Largest Dataset (SipakMed)](https://www.kaggle.com/datasets/prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed)


## Getting Started

To get started with the project, clone the repository and navigate through the directory structure to understand the code and data flow.

### Prerequisites

- Python 3.10
- Required Python packages (listed in `requirements.txt`)

```bash
pip install -r requirements --no-dependencies
```

### Running the FastAPI Application

Navigate to the `api` directory and run the FastAPI application:

```bash
cd api
uvicorn main:app --reload
```

### Jupyter Notebook

Navigate to the `notebook` directory and open the `Cytology_Project.ipynb` to follow through the steps of image extraction, preprocessing, and model training/testing.

```bash
cd notebook
jupyter notebook Cytology_Project.ipynb
```

- LinkedIn - [Diogo Pires](https://www.linkedin.com/in/diogo-f-m-pires)
- GitHub: [diogo-pires-github](https://github.com/diogo-pires-github)
