# Lung Cancer Detection using CNN

## Description
This project aims to build a classifier using a simple Convolutional Neural Network (CNN) to classify normal lung tissues from cancerous tissues. The dataset used includes images for three classes of lung conditions: Normal, Lung Adenocarcinomas, and Lung Squamous Cell Carcinomas. The project has been developed using Google Colab.

## Installation Instructions
To set up the project, follow these steps:
- Clone the repository: `git clone https://github.com/aayush1693/Lung-Cancer-Detection-using-CNN.git`
- Navigate to the project directory: `cd Lung-Cancer-Detection-using-CNN`
- Install the required dependencies: `pip install -r requirements.txt`

## Usage Instructions
To use the project, follow these steps:
1. Ensure that the dataset is downloaded and placed in the appropriate directory.
2. Open the project in Google Colab or a local Jupyter Notebook environment.
3. Run the notebook cells to preprocess the data, train the model, and evaluate the results.

## Dataset Information
The dataset, taken from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images), includes 5000 images for three classes of lung conditions:
- Normal Class
- Lung Adenocarcinomas
- Lung Squamous Cell Carcinomas

These images for each class have been developed from 250 images by performing data augmentation on them.

## Model Architecture and Working
The project uses a Convolutional Neural Network (CNN) to classify lung tissues. The architecture includes convolutional layers, pooling layers, and fully connected layers. The model is trained on the dataset to learn features distinguishing the three classes of lung conditions.

## Development Details
The project has been developed using Google Colab. The development stages include:
- Data Collection and Preprocessing
- Model Building and Training
- Model Evaluation and Testing


## Contributing
Contributions are welcome! Please follow these steps to contribute:
- Fork the repository
- Create a new branch (`git checkout -b feature-branch`)
- Commit your changes (`git commit -am 'Add new feature'`)
- Push to the branch (`git push origin feature-branch`)
- Create a new Pull Request

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
