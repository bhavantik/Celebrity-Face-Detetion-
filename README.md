# Celebrity-Face-Detetion
## Problem Description
- In this Project, We classify an image of sports people. Here, we use OpenCV library for face & eye detection and feature engineering using wavelet transforms. Model building using SVM, Logistic regression, Neural Networks, etc. to classify new image and comparison of its result.
- **Technology used:** OpenCV, Web-Scrapping, Wavelet transform, SVM, Logistics Regression, NNs
  
## Steps
1. Data Collection
2. Data Cleaning 
3. Feature Extraction: Wavelet Transformation
4. Training & Prediction a Model Using SVM
5. Comaparison of Different Model 

## 1. Data Collection
- **Data_collection.ipynb** file mentined above represent Data collection python code using python web scraping.
- Data Collection is Through Python web scraping using **beautifulsoup** python library.
- Here, we Scrap 7 Indian Sports Celebrity for our training and classification purpose.
  
## 2. Data Cleaning 
- **Data_Cleaning.ipynb** file mentined above represent Data Visualization & Cleaning python code.
- Steps:
  - Load images
  - Detect faces with 2 eyes and keep only those images for further process.
  - Crop faces and stored celebrity cropped images in respective folder inside cropped folder.
  - Finally manually checking cropped photo and deleting unwanted photoes.
  
## 3. Feature Extraction: Wavelet Transformation
- Feature Extraction done in above both remaining .ipynb files.
- Here, we use Wavelet transformation for feature extraction.
  
## 4. Training & Prediction a Model Using SVM
- **Training & Prediction using SVM.ipynb** file mentined above represent Training and prediction of new images using SVM classifier.
  
## 5. Comaparison of Different Model 
- **Training model & Prediction-Comparision.ipynb** file mentined above represent Comparision of various classification algorithams.
  
