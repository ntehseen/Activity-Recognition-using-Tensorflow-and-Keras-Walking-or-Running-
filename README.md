
# Activity Recognition using Tensorflow and Keras <Walking or Running>

## Overview

This project aims to recognize human activities, specifically walking and running, in images using deep learning techniques implemented with Tensorflow and Keras. The model is trained on a dataset consisting of images of individuals walking and running, and it can make predictions on new images to classify the activity being performed.

## Project Structure

The project is divided into the following tasks:

1. **Loading Data**: Loading the dataset containing images of walking and running activities.
2. **Data Labelling**: Manually labelling the data to prepare it for training.
3. **Data Preprocessing**: Preprocessing the images through data augmentation and normalization.
4. **Model Training**: Training a deep learning model using transfer learning with the InceptionV3 architecture.
5. **Model Fine-tuning**: Fine-tuning the trained model to improve performance.
6. **Prediction**: Providing a function to make predictions on new images uploaded by the user.

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ntehseen/activity-recognition.git
   ```

2. Navigate to the project directory:

   ```bash
   cd activity-recognition
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Train the model:

   ```bash
   python train_model.py
   ```

2. Make predictions on new images:

   ```bash
   python predict_activity.py --image_paths /path/to/image1.jpg /path/to/image2.jpg --model_path /path/to/trained_model.h5
   ```

## Directory Structure

```
activity-recognition/
│
├── data/                 # Directory for storing dataset images
│   ├── train/            # Training images (walking and running)
│   └── test/             # Test images (walking and running)
│
├── models/               # Directory for saving trained models
│   └── trained_model.h5  # Trained model file
│
├── train_model.py        # Script for training the model
├── predict_activity.py   # Script for making predictions on new images
├── data_preprocessing.py # Script for data loading and preprocessing
├── requirements.txt      # List of project dependencies
└── README.md             # Project overview and instructions
```

## Contributing

Contributions to improve this project are welcomed! If you find any bugs or have suggestions for enhancements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

