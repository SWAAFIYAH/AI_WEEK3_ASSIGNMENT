# AI Tools Assignment - CNN Visualization

This repository contains the implementation of various AI tools and techniques, with a focus on CNN (Convolutional Neural Network) visualization for the MNIST dataset.

## Project Structure

The project is divided into multiple parts, each focusing on different aspects of AI and machine learning:

1. Theoretical Understanding
2. Classical ML with Scikit-learn
3. NLP with spaCy
4. **CNN Visualization** (This component)
5. Ethics & Optimization

## CNN Visualization Component

### Overview
This component demonstrates the visualization of a trained CNN model's predictions on the MNIST dataset. It provides insights into how the model makes its predictions and which parts of the images it focuses on.

### Features
- Loading and using a pre-trained CNN model
- Random selection of test images
- Prediction visualization with confidence scores
- Heatmap generation using Grad-CAM
- Confidence score distribution visualization

### Requirements
```bash
tensorflow
numpy
matplotlib
opencv-python
seaborn
```

### Usage
1. Ensure you have the trained model file (`mnist_cnn_model.h5`) in your working directory
2. Run the visualization notebook:
   ```python
   # Load the model
   model = load_model('mnist_cnn_model.h5')
   
   # Run the visualization code
   # (See CNN_Visualization.ipynb for complete implementation)
   ```

### Visualizations
The code generates three types of visualizations:
1. **Prediction Visualization**: Shows original images with their predicted labels and confidence scores
2. **Heatmap Visualization**: Displays which parts of the images the model focuses on when making predictions
3. **Confidence Score Distribution**: Shows the model's confidence in all possible digit predictions

## Project Components

### 1. Theoretical Understanding
- Comparison of TensorFlow and PyTorch
- Use cases for Jupyter Notebooks
- NLP with spaCy

### 2. Classical ML with Scikit-learn
- Iris Species Dataset classification
- Decision tree implementation
- Model evaluation metrics

### 3. NLP with spaCy
- Named Entity Recognition
- Sentiment analysis
- Text processing

### 4. CNN Visualization (This Component)
- Model prediction visualization
- Confidence score analysis
- Heatmap generation

### 5. Ethics & Optimization
- Bias analysis
- Model optimization
- Ethical considerations

## Getting Started

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the visualization notebook:
   ```bash
   jupyter notebook CNN_Visualization.ipynb
   ```

## Contributing
This project is a collaborative effort. Each team member is responsible for their respective component:
- Member 1: Theoretical Understanding
- Member 2: Classical ML Implementation
- Member 3: NLP Implementation
- Member 4: CNN Visualization (This component)
- Member 5: Ethics & Optimization

## License
This project is part of an academic assignment and is intended for educational purposes.

## Acknowledgments
- MNIST dataset
- TensorFlow team
- Google Colab for providing the development environment 