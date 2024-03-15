# Project Title: Human Activity Predictive Analysis
This project was part of the EE-514 Module of Data analysis and Machine learning at Dublin City University. It focuses on using sensor data to predict human activity and is based on the ExtraSensory dataset, This dataset was collected in 2015-2016 by Yonatan Vaizman and Katherine Ellis with the supervision of Professor Gert Lanckriet. Department of Electrical and Computer Engineering, University of California, San Diego.

The methodology involved in this study is summarized as follows:

1. Importing Relevant Libraries: The Jupyter Notebook was initialized, and essential libraries such as pandas, numpy, matplotlib, sklearn, statistics, and pathlib were imported to facilitate data manipulation, visualization, machine learning modeling, statistical analysis, and file path handling.

2. Data Loading and Attribute Selection: The ExtraSensory dataset was loaded using pandas, and data corresponding to a specific user UUID was selected based on user target attribute. The accelerometer attribute, encompassing both watch acceleration (watch_acceleration) and raw acceleration (raw_acc) was particularly focused on.

3. Logistic Regression Model Training and Evaluation: The selected user data was fed into a logistic regression model for training and evaluation. The trained model was tested on five randomly chosen users to assess the model's ability to accurately predict whether the user is walking or not.

4. Validation Set and Model Performance Assessment: A 20% portion of the dataset was designated as a validation set to evaluate the performance of the logistic regression model and a support vector classifier (SVC) with 'sigmoid' and 'rbf' kernel hyperparameters.

5. Model Evaluation Metrics Generation: Classification reports were generated for each model to provide detailed insights into their performance. Additionally, ROC curves were plotted to visualize the ability of the logistic regression model and SVC to distinguish between walking and non-walking activities.


This project leveraged the following skills:
1. Jupyter Notebooks
2. Python programming
3. Data collection and exploration
4. Data wrangling and cleaning
5. Extract, Transform, and Load (ETL) processes
6. Machine learning techniques
7. Logistic regression modeling
8. Model selection and optimization9. Statistical analysis and predictive modeling
