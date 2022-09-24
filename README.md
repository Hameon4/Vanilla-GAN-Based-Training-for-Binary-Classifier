# Vanilla GAN-Based Training for Binary Classifier <br>
This AI project's aim is to make a custom GAN-model to generate synthetic data and discriminate the two or, in other words, for binary classification. Conditions were to get an RMSE no more than 20% and a low RMSE delta (|pre GAN - post GAN|). The model proved to be consistent in providing RMSEs < 20% and the lowest RMSE delta recorded was 0.003.
<hr>
Intensive testing were implemented on this project, as different methods were tried to determine the best possible combination. Tabular and Pictorial were both tested, and tabular proved to be a better choice. For classification tests, all ensemble learning trees were tried, even supported vector machines (SVMs), and random forest tree had the best results, following xgboost. 
