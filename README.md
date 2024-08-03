# Twitter-Sentiment

This project analyzes the performance of various models on Twitter sentiment data. The analysis is divided into multiple stages, each employing techniques to evaluate and improve model accuracy and interpretability.

### Logistic Regression
- **Objective:** Calculate the accuracy of a logistic regression model on Twitter sentiment data.
- **Approach:** Apply logistic regression and compare its accuracy with other methods.

### Hierarchical Clustering and PCA
- **Objective:** Enhance feature selection and model performance.
- **Approach:** 
  - Create clusters using hierarchical clustering.
  - Apply Principal Component Analysis (PCA) to identify the most important features.
  - Train independent classifiers on these clusters and compare the overall accuracy with the logistic regression model.

### Relu Net Classifier and Local Linear Models
- **Objective:** Improve interpretability while maintaining accuracy.
- **Approach:**
  - Train a Relu net classifier.
  - Develop local linear models by training linear classifiers on clusters based on activation functions.
  - Achieve comparable accuracy to Relu nets, but with the added benefit of increased explainability due to the linear modeling of the black box models.

### Topic Analysis with UMAP, HDBSCAN, and BERTopic
- **Objective:** Understand the topics within each cluster and their distribution.
- **Approach:** Use UMAP for dimensionality reduction, HDBSCAN for clustering, and BERTopic for topic analysis within each cluster.
