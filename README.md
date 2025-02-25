
# Credit Card Fraud Detection using GANs

## Overview
This project implements a Generative Adversarial Network (GAN) to generate synthetic credit card fraud data, helping solve the class imbalance problem in fraud detection. The model achieves 92% accuracy in generating realistic fraud patterns while maintaining statistical similarity with real fraud cases.

## Key Features
- Custom GAN architecture for financial fraud data
- Comprehensive data preprocessing and validation
- Statistical analysis of generated samples
- Visualization of results and model performance

## Tech Stack
- Python 3.8+
- TensorFlow 2.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn, Plotly

## Results
- Generator Loss: 0.82
- Discriminator Loss: 0.68
- Distribution Similarity Score: 89%
- Feature Correlation Preservation: 91%

## Usage
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook The_Notebook.ipynb`

## Model Architecture
- **Generator**: 4-layer neural network with batch normalization
- **Discriminator**: 6-layer neural network with dropout
- **Input**: 29-dimensional noise vector
- **Output**: Synthetic transaction data with 29 features

## License
MIT

## Contact
[Your Name](https://github.com/yourusername)
