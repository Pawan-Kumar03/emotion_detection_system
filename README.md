# Emotion Detection System

## Overview

This Emotion Detection System uses deep learning techniques to classify emotions from images. The project evaluates four models—CNN, CNN with augmentation, VGG16, and ResNet50—to determine the most effective approach for emotion recognition. The final choice is ResNet50, which utilizes transfer learning for enhanced performance. The system is deployed on Gradio for interactive testing and demonstration.

## Key Features

- **Model Evaluation**: Includes CNN, CNN with data augmentation, VGG16, and ResNet50.
- **Advanced Techniques**: Implements early stopping through callbacks, class weights to manage imbalanced data, and thorough data cleaning and scaling.
- **Transfer Learning**: Utilizes ResNet50 with transfer learning for optimal accuracy.
- **Interactive Deployment**: Available via Gradio for real-time interaction.

## Getting Started

### Prerequisites

- Python 3.7+
- Libraries: TensorFlow, Keras, OpenCV, Gradio, NumPy, Pandas, Matplotlib, Scikit-learn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Pawan-Kumar03/emotion_detection_system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd emotion-detection-system
    ```

### Usage

1. **Run in Google Colab.

3. **Access the Demo**: Open the Gradio demo link in your browser:
    [Emotion Detection System Demo](https://df24cb2dc618eb3af0.gradio.live/)

## Model Details

- **CNN**: Basic Convolutional Neural Network for initial testing.
- **CNN with Augmentation**: Enhanced CNN with image augmentation techniques.
- **VGG16**: Utilizes the VGG16 architecture for feature extraction.
- **ResNet50**: Uses the ResNet50 architecture with transfer learning for superior performance.

## Contributing

Feel free to open issues or submit pull requests. Please follow the coding guidelines and ensure your contributions align with the project's goals.



## Acknowledgments

- TensorFlow and Keras for deep learning frameworks
- Gradio for interactive deployment
- The open-source community for various tools and libraries

