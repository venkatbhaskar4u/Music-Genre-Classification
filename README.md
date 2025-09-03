# Music Genre Classification Using Python

## Overview
This project develops a machine learning pipeline for accurately classifying music tracks into genres such as pop, rock, jazz, hip-hop, classical, and more. Leveraging Python and advanced audio processing libraries, the workflow demonstrates robust techniques in feature extraction, supervised learning, and model validation for practical music analysis and categorization.

## Key Features
- Collection of a diverse music dataset spanning multiple genres for reliable training and testing
- Audio feature extraction: spectrograms, MFCCs, tempo, rhythm, pitch, chroma, and genre-specific acoustic signatures
- Model training with SVM, Random Forests, and Convolutional Neural Networks (CNN) for high-accuracy classification
- Comprehensive model evaluation: accuracy, precision, recall, F1-score, and confusion matrix for cross-genre performance
- Genre prediction on new, unseen music tracks
- Visualizations: confusion matrices, genre distribution graphs, and bar charts of model results

## Technologies Used
- Python
- Librosa (audio feature extraction)
- scikit-learn, TensorFlow/Keras (or PyTorch)
- Jupyter Notebook
- NumPy, matplotlib, pandas

## Dataset
- Publicly available labeled music datasets (e.g., GTZAN, FMA, Million Song Dataset)
- Predefined genres with standardized audio preprocessing for modeling

## How to Run
1. Clone this repository: `git clone https://github.com/venkatbhaskar4u/Music-Genre-Classification.git`
2. Download the appropriate music dataset and place in the required directory.
3. Install dependencies:
   pip install -r requirements.txt
4. Launch and run `Music_Genre_Classification.ipynb` in Jupyter.
5. Train models, evaluate genre prediction accuracy, and visualize results.

## Results & Example Outputs
- Achieves up to **X% accuracy** distinguishing genres on public test sets
- Sample output: “Track: jazz_001.wav — Predicted Genre: Jazz”
- Genre distribution summary and confusion matrix visualization

## Applications & Impact
- Improves music recommendation systems and playlist generation
- Enables content-based music retrieval and metadata enrichment
- Supports streaming platforms and academic research in music informatics

## Author
Venkat Bhaskar Reddem
