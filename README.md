# Real-Time-Facial-Emotion-Detection
# Facial Emotion Recognition

## Description
This project implements a Facial Emotion Recognition system using deep learning. It trains a Convolutional Neural Network (CNN) to classify facial expressions into different emotions.

## Features
- Data preprocessing and visualization
- Convolutional Neural Network (CNN) model for emotion classification
- Training and evaluation of the model
- Visualization of training performance and confusion matrix

## Dataset
The dataset consists of images categorized into the following emotions:
- Anger
- Contempt
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprised

## Usage
1. Ensure your dataset is available at the specified directory.
2. Run the script to train the model:
   ```sh
   python main.py
   ```
3. The trained model will classify facial expressions into one of the predefined emotion categories.
4. Model evaluation and visualization will be displayed, including accuracy plots and a confusion matrix.

## Training Details
- Uses a CNN with multiple convolutional and pooling layers.
- Trained with categorical cross-entropy loss and Adam optimizer.
- Model evaluates on a test set split from the dataset.

## Results
The model outputs accuracy and loss plots along with a confusion matrix and classification report for performance evaluation.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or suggestions, feel free to contact [your email or GitHub profile].

