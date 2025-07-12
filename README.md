# Credit-Card-Fraud-Detection

This repository analyzes and provides an understanding of the famous European credit card fraud dataset. The dataset can be found at https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud. The dataset over here is highly “imbalanced” i.e there are way more genuine events than fraud. This resembles a real life scenario where fraud happens in a rare scenario. But it is very important to detect and prevent fraud as its repercussions are very high.

Ensemble techniques like logistic regression, random forest, gradient boost ; binary classification feedforward neural network using ReLU; Support Vector Machine - SVM (Linear Kernel) have been experimented with on both imbalanced and balanced to make observations on there performance.

For balancing the datasets different techniques like undersampling, oversampling and SMOTE have been used.

In-depth study of the different modelling techniques on the imbalanced/balanced has been made.

<img width="478" alt="image" src="https://github.com/user-attachments/assets/42f97c03-116b-45ae-bb1e-ca57c0797c06" />

After performing undersampling,

<img width="458" alt="image" src="https://github.com/user-attachments/assets/6ee6066a-1126-4bd6-bf9e-bff57e2cdb36" />

Oversampling with a random forest classifier has been done,

<img width="529" alt="image" src="https://github.com/user-attachments/assets/afb008b0-7e56-49fb-bf76-d2ac5513a4fb" />

Finally testing has been done by selecting neural network (ReLU) model,

<img width="499" alt="image" src="https://github.com/user-attachments/assets/40fc4b56-cc9a-41de-a77c-5caa080f769c" />

Mainly precision has been used to evaluate the performance of a model as in this particular dataset, confusion matrix accuracy is going to be high due the large imbalance(Far greater number of genuine data points).

Feel free to contribute to this project.





