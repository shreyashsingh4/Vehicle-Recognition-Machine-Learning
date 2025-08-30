# Vehicle Recognition Using Machine Learning

## Overview
This project focuses on vehicle recognition using machine learning techniques to classify different vehicle types based on shape-based feature extraction. The dataset used consists of binary silhouettes of four vehicle models that is — Opel, Saab, a double-decker bus, and a van—captured from various angles. The goal is to accurately classify these vehicles using machine learning algorithms.

## Dataset
The dataset was collected in 1986-87 and consists of binary silhouette images representing different vehicle types. These images were processed using shape-based features such as compactness, circularity, and aspect ratios.

## Methodology
- **Preprocessing:** Image resizing, normalization, and noise reduction.
- **Feature Extraction:** 18 shape-based features were extracted.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) was applied to enhance computational efficiency.
- **Machine Learning Models:**
  - Logistic Regression
  - Naïve Bayes
  - Support Vector Machines (SVM)
  - Decision Trees
  - Random Forests
  - Artificial Neural Networks (ANNs)
  - Clustering (K-Means, Hierarchical Clustering)

## Model Evaluation
Each algorithm was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Silhouette Score (for clustering models)**
- **Calinski-Harabasz and Davies-Bouldin indices**

### Results
- **Best Performing Model:** Random Forest (Accuracy: 78.2%)
- **Alternative Models:** Support Vector Machines (79% accuracy), Decision Trees (73.5% accuracy), k-NN (74% accuracy)
- **Clustering Analysis:** K-Means and Hierarchical Clustering revealed meaningful groupings but were less effective for classification.

## Conclusion
Random Forest emerged as the most effective model for vehicle recognition due to its high accuracy, robustness, and interpretability. The project demonstrates the practical application of classical machine learning techniques in object recognition from 2D images.

## Future Enhancements
- **Real-Time Deployment**: Optimizing the model for embedded systems for real-time vehicle recognition.
- **Data Expansion**: Collecting a more diverse dataset with various lighting and environmental conditions.
- **Hybrid Models**: Combining deep learning with traditional machine learning to improve classification performance.
- **Integration with IoT and Smart City Infrastructure**: Deploying the system for traffic monitoring and automated toll collection.

## Link
https://colab.research.google.com/drive/1uMXG2u54TgMMHIuCueALbeAOHzB9BAlm
