# Fake-Reddit-Prediction

Reddit Fake Post Detection (by Looking Only at the Title)

False information on the Internet has caused many social problems due to the raise of social network and its role in different domains such as politics.
In this project, we are going to predict if a specific reddit post is fake news or not, by looking at its title. The data is raw (contains various forms of words).

The notebook consists of:

1) General Questions & their answers to enhance understanding the problem domain.
2) Problem Questions & their answers to enhance understanding the problem solutions.
3) Import important libraries.
4) Import data.
   - You will find the data link in (https://www.kaggle.com/competitions/cisc-873-dm-f22-a3).
5) Data Exploration.
6) Working on data.
   - I will apply two different cleaning functions on data and see the results of each of them.
   
7) Data Splitting.
8) Example when using word analyzer.
9) Example when using char analyzer.

10) Model(1): LogReg + (analyzer='word') with (Grid Search) using (Validation set)
11) Model(2): LogReg + (analyzer='char') with (Grid Search) using (Validation set)
12) Model(3): LogReg + (analyzer='word') with (Grid Search) using (Cross Validation)
13) Model(4): LogReg + (analyzer='char') with (Grid Search) using (Cross Validation)
14) Model(5): LogReg + (analyzer='word') with (Grid Search) using (Cross Validation)    
    - With different hyperparameter.

15) Model(6): XGBoost + (analyzer='word') with (Random Search) using (Cross Validation)
16) Model(7): RF + (analyzer='word') with (Grid Search) using (Cross Validation)
17) Submission file.


