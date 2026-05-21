
This project demonstrates handwritten digit classification using the K-Nearest Neighbors (KNN) algorithm. The dataset used is the MNIST dataset, which contains a large collection of handwritten digits.

Project Structure
Data Loading and Preprocessing: The MNIST dataset is loaded using tensorflow.keras.datasets. The image data is then normalized by dividing by 255 and flattened into a 1D array.
KNN Model: A K-Nearest Neighbors classifier from sklearn.neighbors is trained on the preprocessed training data.
Model Evaluation: The trained KNN model is evaluated on the test set to determine its accuracy.
Prediction on Sample Data: The model's prediction capabilities are demonstrated on individual test images, including rotated images and images loaded from external files.
Model Persistence: The trained KNN model is saved using joblib for future use.
Key Libraries Used
tensorflow: For loading the MNIST dataset.
matplotlib: For visualizing digit images.
numpy: For numerical operations.
sklearn: For the K-Nearest Neighbors classifier.
pandas: For data manipulation (e.g., creating DataFrames for single image predictions).
cv2 (OpenCV): For image manipulation, specifically for rotating and resizing images.
