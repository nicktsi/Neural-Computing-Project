In my zip folder I have the following files:

1. Smoke_Detection_Project_Testing_Best_Models.ipynb: This is a smaller jupyter notebook which basically loads the test set, then loads the two best, pre-trained models (Best MLP and best SVM) and runs them on the test set. I have made sure that the results are the same and reproducable for both this notebook and the original notebook (Smoke_Detection_Project.ipynb, which i saved as a PDF file) by setting the same torch manual seed in both notebooks. I made this notebook so you can just run the code and see the results. You can also check with the original notebook where all the preprocessing, training, validation etc were made to verify that the testing results are the same in both notebooks. You don't need to necessarily download the X and Y validation and train sets because the best models have already been trained in the original notebook, but I also saved them in case you wish to check anything. So in this notebook, after downloading the best models and the  X and Y test set CSV files, you should be able to run the best models on the test data and see the results without having to do any extra tasks.

2. Best_MLP_Model.pkl: This is the pickle file in which I saved the best MLP model after being trained and validated with its parameters.

3. Best_MLP_Model.pth: This is the pth version of the best MLP model (if you want you can use).

4. Best_SVM_Model.pkl: This is the pickle file in which I saved the best MLP model after being trained and validated with its parameters.

5. X_Test.csv: The X test set which was used in both models for better comparison. This was saved as a CSV file.

6. X_Train.csv: The X train set which was used in both models for better comparison. This was saved as a CSV file.

7. X_Val.csv: The X validation set which was used in both models for better comparison. This was saved as a CSV file.

8. Y_Test.csv: The Y test set which was used in both models for better comparison. This was saved as a CSV file.

9. Y_Train.csv: The Y train set which was used in both models for better comparison. This was saved as a CSV file.

10. Y_Val.csv: The Y validation set which was used in both models for better comparison. This was saved as a CSV file.

11. smoke_detection_iot.csv: The original dataset that was used in this project. This is a CSV file. The dataset was found in Kaggle (https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset ).
