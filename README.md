# Autism-Classifier

1. **SwinTransformer.ipynb**
   - Trains a Swin Transformer model on the AffectNet dataset for facial emotion classification.
   - Utilizes the model to learn facial features and emotions.

2. **SwinTransformer2.ipynb**
   - Uses the pre-trained Swin Transformer model (from the first notebook) as a starting point.
   - Fine-tunes the model on a new dataset to classify autism in children.

## File Descriptions
- `SwinTransformer.ipynb`: Code for training the Swin Transformer on AffectNet.
- `SwinTransformer2.ipynb`: Code for using the pre-trained model for autism classification.
- `ASD/`: Directory containing dataset folders and saved model files.

## Usage
1. Execute `SwinTransformer.ipynb` to train the model on AffectNet.
2. Execute `SwinTransformer2.ipynb` to use the pre-trained model for autism classification.

## Requirements
- Python 3.x
- TensorFlow
- Matplotlib
- NumPy
- scikit-learn
