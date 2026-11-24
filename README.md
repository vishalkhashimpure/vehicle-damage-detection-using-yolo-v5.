
Car Damage Detection Using MobileNetV2 and yolo v5
About the Project
This project is about detecting car damage using Deep Learning and Computer Vision. The main idea is to build a model that can look at a car image and predict whether the car is damaged or not.

For this project, I used the MobileNetV2 pre-trained model with Transfer Learning. I trained the model using a dataset containing images of damaged and undamaged cars.

The model takes an input image and classifies it into one of two categories: Damaged or Not Damaged.
Technologies Used
- Python
- TensorFlow
- Keras
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
Dataset
I used a car damage detection dataset containing two categories:
- 00-damage: Images of damaged cars.
- 01-whole: Images of cars without visible damage.
The images were resized to 224 × 224 pixels before training the model.
Project Steps
1. Data Collection

Collected images of damaged and undamaged cars for training and testing the model.

2. Data Preprocessing

Loaded the images, resized them and prepared the data for model training. I also converted the class labels into the required format.

3. Data Augmentation

Applied image augmentation techniques to introduce variations in the training images and help the model learn better.

4. Model Building

Used MobileNetV2, a pre-trained CNN model, and added classification layers to identify damaged and undamaged cars.

5. Model Training

Trained the model using the prepared dataset for 50 epochs.

6. Model Evaluation

Checked the model's performance using accuracy, precision, recall and F1-score.

7. Prediction

Tested the trained model with a car image to check whether it could correctly identify the vehicle as damaged or undamaged.
Model Performance
After training and testing, the model achieved approximately 83% accuracy on the test dataset.

Car-Damage-Detection/
│
├── car-damage-detection.ipynb
│
├── README.md
│
└── Dataset/
    ├── 00-damage/
    └── 01-whole/

What I Learned
While working on this project, I got practical experience with:
- Working with image datasets.
- Image preprocessing and augmentation.
- Understanding CNN and Transfer Learning.
- Using MobileNetV2 for image classification.
- Training and evaluating a Deep Learning model.
- Making predictions using a trained model.
Future Improvements
- Improve the model's prediction accuracy.
- Try other pre-trained Deep Learning models.
- Build a simple web application for uploading car images and getting predictions.
- Explore identifying the specific damaged parts of a vehicle.
