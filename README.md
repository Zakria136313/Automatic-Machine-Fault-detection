# Machine Fault Detection Using Deep Learning

## Overview
This project presents an innovative approach to identifying machine faults using **Deep Learning** techniques on **Acoustic Data**. The system is designed to detect four key fault types: **Arcing**, **Corona**, **Looseness**, and **Tracking**. Leveraging Mel Spectrogram images derived from audio data, the solution efficiently classifies these faults using a robust **Convolutional Neural Network (CNN)** model.

## Key Features
- Transforms audio data into **grayscale spectrogram images** for model training.  
- Ensures a balanced dataset with an **80/20 split** for training and testing.  
- Implements a CNN architecture tailored for effective fault detection.  
- Provides a detailed **Confusion Matrix** for visualizing model performance.  

## Step-by-Step Workflow
1. **Data Preparation**  
   - Import `.wav` files containing machine sound patterns.  
   - Segment each audio sample into 0.5-second clips with a 0.2-second overlap.  
   - Generate Mel Spectrogram images from each segment.  
2. **Data Splitting**  
   - Automatically partition data into **80% training** and **20% testing** sets.  
3. **Model Training**  
   - Train a CNN model with three convolutional layers and fully connected layers for classification.  
4. **Evaluation**  
   - Assess model performance using **Test Accuracy** and a comprehensive **Confusion Matrix**.  

## System Requirements
- **Python 3.x**  
- **TensorFlow/Keras**  
- **Librosa** for audio data manipulation  
- **Matplotlib** for visualizing Mel Spectrograms  
- **Scikit-learn** for generating the Confusion Matrix  

## Usage Instructions
1. **Dataset Preparation:** Upload `.wav` audio files to Google Drive.  
2. **Run the Code:** The provided code will:
   - Convert audio data into spectrogram images.  
   - Divide data into training and testing sets.  
   - Train the CNN model and evaluate its performance.  
3. **Results Analysis:** The system will display the model's **accuracy** and a **confusion matrix** for deeper insights.

## Achievements
- The model has demonstrated strong accuracy in identifying machine faults.  
- Effective fault categorization across the four identified types.

## Potential Improvements
- Enhance performance through hyperparameter optimization.  
- Deploy the solution on embedded systems such as a **Raspberry Pi** for real-time fault detection.  

## Supervision
- Guided by **Engr Ahmad Khawaja**

## License
This project is licensed under the **MIT License** for public use and distribution.
