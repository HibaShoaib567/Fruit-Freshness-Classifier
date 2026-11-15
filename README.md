# 🍎 Fruit Freshness Classifier

An AI-powered Fruit Freshness Classification system built using Deep Learning and Transfer Learning techniques. The project identifies different fruit types and determines whether they are Fresh or Rotten using image classification.

The final model uses an **Improved MobileNetV2 architecture** and achieves **91.37% validation accuracy** across 30 classification classes.

## 🎯 Project Overview

The Fruit Freshness Classifier is designed to automatically analyze fruit images and predict their freshness condition.

It classifies 15 fruit categories into two conditions:

- Fresh
- Rotten

The project explores multiple deep learning architectures, compares their performance, and selects Improved MobileNetV2 as the final model.

## ✨ Key Features

- Classification of 15 different fruit categories.
- Detection of Fresh and Rotten fruit conditions.
- Image upload for individual predictions.
- Prediction confidence scores.
- Top 5 prediction results.
- Model performance comparison.
- Confusion matrix and classification report.
- Deep learning-based image classification.

## 🍇 Dataset Information

**Dataset:** Freshness44

The dataset contains images of different fruits categorized according to their freshness condition.

**Fruit Categories:**

1. Apple
2. Banana
3. Grape
4. Grapes
5. Guava
6. Jujube
7. Kaki
8. Mango
9. Orange
10. Papaya
11. Peach
12. Pear
13. Pomegranate
14. Strawberry
15. Watermelon

**Classification Details:**
- Fruit Categories: 15
- Freshness Conditions: 2
- Total Output Classes: 30

## 🧠 Models Implemented

Four model configurations were explored and compared:

| Model | Validation Accuracy |
|---|---:|
| CNN | 59.25% |
| MobileNetV2 | 76.31% |
| Fine-tuned MobileNetV2 | 76.77% |
| Improved MobileNetV2 | **91.37%** |

The Improved MobileNetV2 model was selected as the final model based on its validation performance.

## 📊 Final Model Performance

The final Improved MobileNetV2 model achieved the following results:

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 91.37% |
| Macro Precision | 92.55% |
| Macro Recall | 90.78% |
| Macro F1-Score | 91.54% |
| Validation Images | 7,750 |

## ⚙️ Model Configuration

- Architecture: Improved MobileNetV2
- Pretrained Weights: ImageNet
- Input Image Size: 160 × 160 × 3
- Batch Size: 32
- Number of Classes: 30
- Optimizer: Adam
- Data Augmentation: Random Flip, Rotation, Zoom and Contrast
- Transfer Learning: Yes

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🔄 Project Workflow

1. Dataset Collection
2. Data Loading and Exploration
3. Image Preprocessing
4. Image Resizing and Normalization
5. Data Augmentation
6. CNN Model Development
7. MobileNetV2 Transfer Learning
8. Model Fine-tuning and Improvement
9. Model Performance Comparison
10. Final Model Evaluation
11. Fruit Freshness Prediction

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Fruit-Freshness-Classifier.git
```

### Step 2: Open the Notebook

Open `final_ANN_v1(2).ipynb` using Google Colab.

### Step 3: Upload or Connect the Dataset

Connect your Google Drive and update the dataset path according to your folder location.

### Step 4: Install Dependencies

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn pillow
```

### Step 5: Run the Notebook

Execute the notebook cells in Google Colab to preprocess the dataset, train the models, evaluate their performance, and generate fruit freshness predictions.

**Note:** The final trained model is saved separately as a `.keras` file. The dataset and trained model must be available at their configured paths to run the corresponding cells.

## 📁 Repository Structure

```text
Fruit-Freshness-Classifier/
│
├── final_ANN_v1(2).ipynb
│
├── README.md
│
├── requirements.txt
│
├── results/
│   ├── model_accuracy_comparison.png
│   └── final_model_metrics.png
│
└── model/
    └── mobilenetv2_improved_best.keras
```

*The structure above is suggested. Add the model and result files only if you upload them.*

## 🔮 Future Enhancements

- Develop a web-based fruit freshness detection application.
- Integrate real-time camera-based fruit classification.
- Expand the dataset with additional fruit categories.
- Improve model generalization and prediction reliability.
- Deploy the trained model for practical use.

## 👩‍💻 Author

**Hiba Shoaib**

Computer Science & Software Engineering

## 📌 Project Purpose

This project was developed for educational and academic purposes to explore Artificial Intelligence, Deep Learning, Transfer Learning, and Image Classification.
