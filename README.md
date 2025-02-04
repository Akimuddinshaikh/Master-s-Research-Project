Analysis of Scalable and Efficient Approaches for Liver Disease Detection
A Hybrid Approach Using Texture-Based Features & Deep Learning

📌 Author: Akimuddin Aslam Shaikh
📍 Institution: National College of Ireland


📌 Project Overview
Liver disease detection using machine learning and deep learning techniques has gained attention for its potential to improve diagnostic accuracy and patient outcomes. This study introduces a unique hybrid approach by combining texture-based Gray-Level Co-occurrence Matrix (GLCM) features with high-dimensional deep learning features extracted from ResNet50.

The research focuses on leveraging unlabeled medical imaging datasets by integrating unsupervised clustering (KMeans, Agglomerative Clustering) with supervised classification (Random Forest, SVM, XGBoost). The results show a scalable and efficient methodology for detecting liver diseases with high precision.

🔍 Key Highlights
✅ Extracted GLCM features and ResNet50 deep learning features from medical imaging datasets.
✅ Implemented unsupervised clustering (KMeans & Agglomerative Clustering) to generate pseudo-labels.
✅ Trained classifiers (Random Forest, SVM, XGBoost) using extracted feature sets.
✅ Combined features (GLCM + ResNet50) with cluster labels for improved classification accuracy.
✅ Achieved near-perfect accuracy (99%-100%) in specific combinations but addressed overfitting concerns.

📊 Machine Learning Techniques & Results
Feature Set	Clustering Method	Classifier	Accuracy
ResNet50 Features	KMeans	RF/SVM/XGBoost	~95%
ResNet50 Features	Agglomerative Clustering	RF/SVM/XGBoost	99%-100%
GLCM Features	KMeans	RF/SVM/XGBoost	~98%
GLCM Features	Agglomerative Clustering	RF/SVM/XGBoost	100% (Potential Overfitting)
GLCM + ResNet50 Features	KMeans	SVM	~96%
GLCM + ResNet50 Features	Agglomerative Clustering	SVM	99%
🔹 Key Finding: Combining ResNet50 deep learning features with Agglomerative Clustering labels yielded the highest classification accuracy (99%-100%), significantly outperforming other combinations.
🔹 Overfitting Observed: Results exceeding 99% accuracy in real-world medical datasets indicate a potential overfitting issue, requiring further validation.
🔹 Pseudo-Labeling Approach Improved Performance: Integrating pseudo-labeling from clustering techniques enhanced classification accuracy.

🛠️ Technologies & Tools Used
Python 🐍
Scikit-Learn (Machine Learning Models)
TensorFlow/Keras (Deep Learning & ResNet50)
OpenCV (GLCM Feature Extraction)
SciPy & NumPy (Clustering & Statistical Analysis)
Matplotlib & Seaborn (Data Visualization)
📌 Results & Insights
✅ GLCM + ResNet50 features provide a robust framework for liver disease detection.
✅ Agglomerative Clustering outperformed KMeans in feature representation.
✅ Pseudo-labeling from clustering significantly improved classification accuracy.
✅ The study presents a scalable, efficient, and high-precision methodology for medical imaging analysis.

📌 Future Work
✔ Validate the approach on larger and more diverse medical imaging datasets.
✔ Implement Transfer Learning with advanced architectures (e.g., Vision Transformers).
✔ Optimize feature selection to mitigate overfitting risks.
✔ Develop an explainable AI (XAI) model to enhance medical interpretability.

