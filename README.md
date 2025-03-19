# Heart Disease Detection Using AI

## Overview
This project is part of the **AI-MedX Rhapsody Healthcare Challenge**. It aims to detect heart disease using deep learning with PyTorch. The model is trained on the **UCI Heart Disease dataset** and achieves an accuracy of **85.85%**.

## Dataset
- **Source**: [Insert Dataset Link]
- **Features**: Age, Blood Pressure, Cholesterol, Heart Rate, etc.
- **Target Labels**: 0 (No Disease) / 1 (Heart Disease)

## Model Architecture
- **Input Layer**: 13 features
- **Hidden Layers**: 3 layers with ReLU activation
- **Output Layer**: 2 neurons (Binary classification: Healthy vs. Diseased)
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam (learning rate = 0.005)
- **Training**: 50 epochs

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [Insert GitHub Repo Link]
   cd heart-disease-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run training script:
   ```bash
   python train.py
   ```
4. Test the model:
   ```bash
   python test.py
   ```

## Results
| Metric     | Score  |
|------------|--------|
| Accuracy   | 85.85% |
| Precision  | 89.2%  |
| Recall     | 91.4%  |
| F1-Score   | 90.3%  |

## Model File
- Trained Model: `heart_disease_model.pth`
- Dataset: [Insert Dataset Link]

## Future Improvements
- Hyperparameter tuning for better accuracy
- Feature engineering to enhance dataset quality
- Deployment using a web-based interface

## Author
Jasmin Shaik
Venkatesh Barla
