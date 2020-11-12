# machine-learning-challenge
 
5 machine learning algorymths were test to predict exoplanets.  Rows with NA values were dropped.  Initial models did not use any of the error data which reduced the accuracy of the model.  The best model created was a deep learning model yielding 89.9% accurate and saved as ClangDeep_42_20_100.h5.  

GridSearchCV (model_1):
This was the first algorythm tested and yielded a score of 0.83.  The model was able to accurately predict false positives at 98%.  Candidate and cofirmed were 60% accurate.

KNeighborsClassifier (model_2):
No error variables were used for this model and yielded a score of .78 at leveled off at k=5

Neural Net and Deep Learning (model_3):
The best nearal net model used 40 inputes 42 nodes and 100 epochs yeilding an accuracy of 88.9%.  The best deep learning model and best model overall used 40 inputes with a 43 node layer and a 10 node layer with 100 epoch yielding an accuracy of 89.9%.

Random Forest (model_4):
The best model generate used an n_estimator of 500 yielding a score of 88%.  The top three variables influencing the model were koi_fpflag_co, koi_fpflag_nt, and koi_fpflag_ss.


