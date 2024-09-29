
Prediction of Glaucoma using machine learning algorithms

  Abstract:
  
The study focuses on creating a prediction model using OCT scans and fundus images of the eye. Features were extracted using deep learning models VGG16 and Inception V3. Various machine learning algorithms, including Logistic Regression, Support Vector Machine (SVM), Random Forest, Bagging Classifier, and Decision Tree, were evaluated for their performance in predicting glaucoma. The models' accuracy and AUC (Area Under the Curve) were measured, showing diagnostic performance with accuracy values between 0.60 to 0.80 and AUC values between 0.50 to 0.65.

  Methodology:
  
1.  Data Collection :
   - Data comprised 650 eye samples (182 glaucoma negative, 482 glaucoma positive) in fundus-sorted images.
   - Features included the cup-to-disc ratio and whether glaucoma was present.

2.  Pre-processing :
   - Images were resized and normalized to a (75x75) pixel format for consistency with the deep learning models.
   - Normalization was done to scale pixel values between 0 and 1.

3.  Feature Extraction :
   - Utilized deep learning models VGG16 and Inception V3 for extracting features from images.

4.  Model Selection :
   - Machine learning models tested included Random Forest, SVM, Logistic Regression, Bagging Classifier, and Decision Tree.

5.  Evaluation :
   - Performance was measured using accuracy and AUC values.
   - Comparative graphs of model accuracies and ROC (Receiver Operating Characteristic) curves were used to identify the most suitable model.

  Results:
  
-  VGG16 and Inception V3 : These models were employed for feature extraction.
-  Model Performance : The models showed varying degrees of accuracy and AUC, indicating their potential effectiveness in predicting glaucoma. The evaluation identified that no single model was superior, and each had its strengths.

  Conclusion:
  
The project aims to advance glaucoma management and prediction. By identifying the most accurate and interpretable machine learning algorithms, the study aspires to develop a dependable tool for early glaucoma detection, potentially improving patient outcomes and reducing the burden of glaucoma-related visual impairment.

