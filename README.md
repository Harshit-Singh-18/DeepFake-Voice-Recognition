# Deep Fake Audio Detection

## Description

This project focuses on detecting deep fake audio using advanced machine learning techniques. Raw audio data was processed using the `librosa` library, transforming it into inputs suitable for Convolutional Neural Networks (CNNs). To enhance model performance, data augmentation and class balancing were implemented using `RandomOverSampler`. The model was trained with dropout and early stopping techniques to ensure reliable audio classification, leveraging TensorFlow and Keras.

## Features

- **Audio Processing:** Utilized `librosa` to preprocess and transform raw audio data into CNN-ready inputs.
- **Data Augmentation & Balancing:** Applied `RandomOverSampler` to address class imbalances and enhance model performance.
- **Model Training:** Employed dropout and early stopping methods to improve the reliability of audio classification.
- **Frameworks:** Used TensorFlow and Keras for building and training the deep learning model.

## Installation

To set up this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes.
4. Push your branch to your fork.
5. Create a pull request.
