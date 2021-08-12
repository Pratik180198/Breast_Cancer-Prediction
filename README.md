# Breast_Cancer-Prediction
Classifying malignant and benign tumors using Machine Learning

# What is Breast Cancer?

Cancer occurs when changes called mutations take place in genes that regulate cell growth. The mutations let the cells divide and multiply in an uncontrolled, chaotic way. The cells keep on proliferating, producing copies that get progressively more abnormal. In most cases, the cell copies eventually end up forming a tumor.

Breast cancer occurs when a malignant (cancerous) tumor originates in the breast. As breast cancer tumors mature, they may metastasize (spread) to other parts of the body. The primary route of metastasis is the lymphatic system which, ironically enough, is also the body's primary system for producing and transporting white blood cells and other cancer-fighting immune system cells throughout the body. Metastasized cancer cells that aren't destroyed by the lymphatic system's white blood cells move through the lymphatic vessels and settle in remote body locations, forming new tumors and perpetuating the disease process.

Breast cancer is not just a woman's disease. It is quite possible for men to get breast cancer, although it occurs less frequently in men than in women. Our discussion will focus primarily on breast cancer as it relates to women but it should be noted that much of the information is also applicable for men.

Breast cancer is the most common type of cancer in women. When cancers are found early, they can often be cured. There are some devices that detect the breast cancer but many times they lead to false positives, which results is patients undergoing painful, expensive surgeries that were not even necessary. These type of cancers are called benign which do not require surgeries and we can reduce these unnecessary surgeries by using Machine Learning. We take a dataset of the previous breast cancer patients and train the model to predict whether the cancer is benign or malignant. These predictions will help doctors to do surgeries only when the cancer is malignant, thus reducing the unnecessary surgeries for woman.

## Objective:
The repository is a learning exercise to:

Apply the fundamental concepts of machine learning from an available dataset
Evaluate and interpret my results and justify my interpretation based on observed data set

1. Identifying the problem and Data Sources
2. Exploratory Data Analysis
3. Build model to predict whether breast cell tissue is malignant or Benign

### Identifying the problem and Getting data.

Identify the types of information contained in our data set In this notebook I used Python modules to import external data sets for the purpose of getting to know/familiarize myself with the data to get a good grasp of the data and think about how to handle the data in different ways. 

### Exploratory Data Analysis

Explore the variables to assess how they relate to the response variable In this notebook, I am getting familiar with the data using data exploration and visualization techniques using python libraries (Pandas, matplotlib, seaborn. Familiarity with the data is important which will provide useful knowledge for data pre-processing)

### Predictive model using Support Vector Machine (svm)

Construct predictive models to predict the diagnosis of a breast tumor. In this notebook, I construct a predictive model using SVM machine learning algorithm to predict the diagnosis of a breast tumor. The diagnosis of a breast tumor is a binary variable (benign or malignant). I also evaluate the model using confusion matrix the receiver operating curves (ROC), which are essential in assessing and interpreting the fitted model.

I had also used different algorithms like KNN and Logistic Regression but SVM works better.
