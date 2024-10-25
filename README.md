# Bone-Fracture-Detection
Bone Fracture Detection using deep learning. This project employs Convolutional Neural Networks (CNNs) to classify fractures in the elbow, hand, and shoulder. Trained on the MURA dataset, it aims to automate fracture detection with high accuracy, leveraging musculoskeletal radiograph data.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contribution](#contribution)
- [License](#license)

## Features
Automated detection of bone fractures.
Classifies fractures across multiple bone types: elbow, hand, and shoulder.
Visualizes model performance metrics.

## Technologies Used
Python
TensorFlow/Keras for deep learning
OpenCV for image processing
Matplotlib and Seaborn for visualizations

## Installation
1. **Clone the repository**:
    git clone https://github.com/Bilal976r/bone-fracture-detection.git
    cd bone-fracture-detection
2. **Install dependencies**:
    pip install -r requirements.txt

## Usage
1. **Prepare the dataset**: Place the MURA dataset in the appropriate directory as specified in the code.
2. **Train the model**: Run the training script to start training the model:
    python training_parts.py
    python training_fracture
3. **Evaluate the model**: Use the evaluation script to assess the model's accuracy:
    python prediction_test.py
    python predictions.py
4. **Main File**: Use this to start the application.
   python mainGUI.py

## Dataset
The project uses the MURA dataset, a large collection of musculoskeletal radiographs. You need to download it separately from [Stanford ML Group's website](https://stanfordmlgroup.github.io/competitions/mura/).

## Results
The model's accuracy, confusion matrix, and other performance metrics will be displayed after training and evaluation. You can customize the visualization scripts for more in-depth analysis.

## Contribution
Contributions are welcome! Feel free to open issues, submit feature requests, or make pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
