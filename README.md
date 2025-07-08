# Teeth Classification with CNN
This project performs image classification of dental images into 7 classes using a CNN built from scratch in TensorFlow.

## Dataset Description
The dataset contains RGB images of teeth categorized into **7 dental conditions**:
- **CaS** – Candidiasis
- **CoS** – Composite restoration
- **Gum** – Gum-related condition
- **MC** – Metal crown
- **OC** – Orthodontic case
- **OLP** – Oral lichen planus
- **OT** – Other conditions

## Files Included
- `Teeth_Classification.ipynb`: full pipeline with preprocessing, augmentation, training, and evaluation
- `plots`: visual outputs like class distribution and confusion matrix
- `requirements.txt`: Python packages used

## How to Run
1. Open the notebook in Colab or Jupyter
2. Mount Google Drive and place the dataset in the right folder
3. Run all cells step by step

## Model Summary
- CNN with 3 Conv2D layers and 1 Dense classifier
- Used `categorical_crossentropy`
- Data augmentation + normalization applied

## Results
- Training Accuracy: 75%
- Testing Accuracy: 77%
- Confusion Matrix and Plots in `plots` folder
