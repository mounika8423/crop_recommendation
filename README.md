Crop Recommendation System using CNN and KNN



Project Description::
This project implements a hybrid crop recommendation system combining deep learning and machine learning techniques. A Convolutional Neural Network (CNN) is used to classify soil types from soil images, and a K-Nearest Neighbors (KNN) model recommends suitable crops using soil and environmental parameters such as NPK values, pH, temperature, humidity, and rainfall.



Objectives::
Classify soil types automatically from images using CNN
Recommend suitable crops based on soil and climatic conditions
Integrate image-based analysis with numerical data



Methodology::
Soil Image Classification (CNN)
Soil images are trained using a CNN model
The model predicts soil type (Alluvial, Black, Clay, Red)
Crop Recommendation (KNN)
Numerical features include N, P, K, pH, temperature, humidity, and rainfall
Predicted soil type is used as an additional feature
KNN recommends crops based on similarity with historical data


Dataset::
Soil Image Dataset: Kaggle (used for CNN training)
Crop Recommendation Dataset: Kaggle (NPK, pH, weather data)
Datasets are not included in the repository due to size constraints.



Project Structure::
crop\_recommendation/
├── notebooks/
│   ├── 01\_soil\_image\_eda.ipynb
│   ├── 02\_cnn\_soil\_classification.ipynb
│   ├── 03\_crop\_data\_eda.ipynb
│   └── 04\_knn\_crop\_recommendation.ipynb
├── src/
│   ├── cnn\_model.py
│   ├── knn\_model.py
├── data/
├── models/
├── README.md
└── .gitignore

Results::
CNN achieved approximately 80–85% validation accuracy
KNN successfully recommended crops based on soil and environmental similarity



Future Scope::
Use pretrained CNN models for better accuracy
Increase dataset size
Deploy as a web application



Technologies Used::
Python
TensorFlow / Keras
Scikit-learn
OpenCV
NumPy, Pandas, Matplotlib


Conclusion::
This project demonstrates the integration of soil image classification and data-driven crop recommendation, highlighting the application of machine learning techniques in precision agriculture.



