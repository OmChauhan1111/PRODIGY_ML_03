🐱🐶 Cat vs Dog Image Classification using SVM
This project is a simple image classification model that uses Support Vector Machines (SVM) to distinguish between images of cats and dogs. It includes image preprocessing, model training, evaluation, and result visualization.

📁 Dataset
Path: C:\Users\omcha\Machine learning\Task3\train

Structure:

markdown
Copy
Edit
train/
├── cats/
│   ├── cat1.jpg
│   ├── ...
└── dogs/
    ├── dog1.jpg
    ├── ...
Images: .jpg format

Labels:

Cat → 0

Dog → 1

🎯 Objective
Load and preprocess image data

Train an SVM model to classify cats and dogs

Evaluate model performance

Visualize model predictions

🛠️ Tools & Libraries
Python

OpenCV (cv2)

NumPy

Scikit-learn (SVC, train_test_split, StandardScaler)

Matplotlib

🧪 How It Works
Load Images:
Reads .jpg files, resizes them to 64x64 pixels.

Preprocessing:

Flatten image pixels

Normalize features using StandardScaler

Split into training and testing datasets (80/20)

Model Training:
Trains a Linear SVM on the processed image data.

Evaluation:
Prints classification report and accuracy.

Visualization:
Displays random predictions with color-coded titles:

✅ Correct = Green

❌ Incorrect = Red

📊 Results
Model: Linear SVM

Accuracy: (printed in terminal after running)

Classification Report: Includes precision, recall, and F1-score
