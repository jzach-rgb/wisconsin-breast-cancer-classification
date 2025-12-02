# wisconsin-breast-cancer-classification
GPIP internship Machine Learning Project

This project Analyzes the Kaggle Wisconsin Breast Cancer Dataset and builds several ML models to
classify tumors either benign or malignant. 

**Workflow includes:**
- Data Cleaning
- Exploratory Data Analysis (EDA
- ML Models 
- PCA decomposition and Variance analysis
- Feature Correlation and visualization
- Analysis and interpretations

**Tools used:**
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

**ML Models Used:**
- Logestic Regression 
- SVM 
- Random Forests

LR and SVM was created alongside a confusion matrix to ensure accuracy

 |  Model     |   Accuracy  |
 ----------------------------
 | Logestic R |    0.9561   |  
 | SVM        |    0.9438   | 


**Findings**:
- Logestic Regression achieved strongest accuracy amoung the tested models.
- Area Worst and Concave Points Worst were amoung the most important predictive features
- PCA showed Concave Points Mean contributed significantly to total variance.
- EDA revealed strong correlations between certain geometric tumor features.


This project was completed as part of my GPIP internship. It demonstrates my ability to:
- Work with real datasets
- Build ML pipelines
- Visualize and interpret data
- Communicate results clearly


Correlation Heatmap:
<img width="882" height="681" alt="image" src="https://github.com/user-attachments/assets/3c81fa0b-79d8-4dca-ad5c-db90ee1231b4" />


Pair Plots (size, shape, texture, and symmetry)
<img width="990" height="931" alt="image" src="https://github.com/user-attachments/assets/f3bb1863-761f-4584-980e-dae9bc324216" />
<img width="908" height="856" alt="image" src="https://github.com/user-attachments/assets/3d108b1f-e250-46e5-96cc-ea0c9cca9852" />
<img width="911" height="837" alt="image" src="https://github.com/user-attachments/assets/48f04ecd-dd4f-4549-9215-d6e91fed1e61" />
<img width="945" height="837" alt="image" src="https://github.com/user-attachments/assets/4f73990f-faac-485c-8cb7-28344af3cd2f" />


Bar Plot of Diagnosis Count:
<img width="468" height="372" alt="image" src="https://github.com/user-attachments/assets/a2b50df4-34fb-41a4-aac0-156467e28571" />


Box plots (in groups of size, shape, texture, and symmetry):
<img width="781" height="332" alt="image" src="https://github.com/user-attachments/assets/0be2b942-acff-487e-9f44-627c041274c8" />
<img width="770" height="322" alt="image" src="https://github.com/user-attachments/assets/872ecb50-441b-4e7e-963f-6c168cfdc8e9" />
<img width="782" height="322" alt="image" src="https://github.com/user-attachments/assets/579e8dc7-bb91-490d-8101-2205fa9d334a" />
<img width="770" height="332" alt="image" src="https://github.com/user-attachments/assets/5b4ab84a-ccec-4672-abd7-82015a2c174b" />


Logestic Regression of the data after 2D PCA:
<img width="395" height="308" alt="image" src="https://github.com/user-attachments/assets/a91c44f1-a646-45e8-9fb8-08e8609a385b" />


SVM model of the data after 2D PCA:
<img width="395" height="308" alt="image" src="https://github.com/user-attachments/assets/4ad2be8e-cd21-4ccd-904a-2c86f0fb4004" />


Loss chart of Logestic Regression and SVM:
<img width="605" height="299" alt="image" src="https://github.com/user-attachments/assets/9cfecaab-2b3b-4b82-b9e7-346ba3b8ef24" />


Table of confusion matrices of LR and SVM
<img width="461" height="269" alt="image" src="https://github.com/user-attachments/assets/3b8a11c3-a378-4b79-a019-c2649f0a536e" />


F1 table of LR and SVM:
<img width="659" height="273" alt="image" src="https://github.com/user-attachments/assets/8c28993b-c62d-42aa-9026-c5aab6d9cb94" />


PCA signifcance table:
<img width="681" height="259" alt="image" src="https://github.com/user-attachments/assets/22d93567-cdaa-42b2-8b37-61c0e27846cf" />


Logestic Regression models per Feature Group:
<img width="385" height="305" alt="image" src="https://github.com/user-attachments/assets/92ded059-2cf2-430f-a8e9-19c5eecd41dd" />
<img width="385" height="305" alt="image" src="https://github.com/user-attachments/assets/f8cd8d63-9d3a-48bc-b6a2-38da678f9bbb" />
<img width="385" height="305" alt="image" src="https://github.com/user-attachments/assets/51910436-a9e9-4ab0-a0f9-10332e81ce75" />
<img width="899" height="331" alt="image" src="https://github.com/user-attachments/assets/1e1d81d5-07e3-4944-acea-419aeb02be4d" />

F1 tables of Logestic Regression models per Feature Group:
<img width="332" height="214" alt="image" src="https://github.com/user-attachments/assets/e38ce55b-6926-43a6-b140-e8987dc7b6c5" />
<img width="339" height="214" alt="image" src="https://github.com/user-attachments/assets/fe837b0b-306d-4cb4-816b-711966d75be2" />
<img width="339" height="214" alt="image" src="https://github.com/user-attachments/assets/5f7eb47f-6929-43eb-a51d-6d6937e0d934" />
<img width="339" height="214" alt="image" src="https://github.com/user-attachments/assets/485868e1-af33-4497-9c43-52992f4db066" />


Random Forest Feature Importance:
<img width="660" height="394" alt="image" src="https://github.com/user-attachments/assets/50dcf122-7f90-46d6-8194-1844b4c8fb48" />







