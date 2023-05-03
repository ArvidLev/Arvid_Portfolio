# Arvid_Portfolio
# [Project 10: Object Detection: Hand Signals](https://github.com/ArvidLev/ObjectDetectionHands)
![image](https://github.com/ArvidLev/Arvid_Portfolio/blob/main/image/thumbsup.png)
For this project we trained a object detection model on 3 hand signals. Hello (wave), good (thumbs up), and small (pinch). Using the Tensorflow Object Detection API, transforming images and annotations to TFrecords, and evaluating model using tensorboard.
# [Project 9: PCA](https://github.com/ArvidLev/PCA)
For this short project I went over the theory behind Principal Component Analysis and created my own PCA function.
![image](https://github.com/ArvidLev/Arvid_Portfolio/blob/main/image/PCA_PCA.ipynb%20at%20main%20%C2%B7%20ArvidLev_PCA%20%C2%B7%20GitHub.png)
# [Project 8: NLP with Python: Covid-19 Tweets](https://www.kaggle.com/arvidlevander/covid-19-nlp)
For this project we are trying classify the sentiment of tweets regarding Covid-19. 
We are going to use Tensorflow and Keras to perform NLP, more specifically we will be using techinques such as:
 - Tokenizing
 - Padding
 - Embedding
 - GRU
 - LSTM
 - Convolutions
 - Dropout

There will also be some data cleaning and reduction of vocabulary to increase the performance of our models.
We will achieve about 88% accuracy on the validation data.
![image](https://user-images.githubusercontent.com/89865352/140621655-215be6ff-cfb7-4de1-a56e-6fb58502a973.png)
# [Project 7: Computer Vision with Python: Cats Vs Dogs](https://github.com/ArvidLev/CatVSDogs)
For this project I am using convultional neural networks to create a model that can classify if pictures of dogs and cats. For this I am using Python with Tensorflow. For this I am using techniques such as preprocessing, data augmentation, transfer learning and fine tuning.
![image](https://user-images.githubusercontent.com/89865352/139783326-d8285333-320c-4fb6-b789-03826510f5df.png)

# [Project 6: Computer Vision with Python: MNIST Kaggle](https://github.com/ArvidLev/MNIST-Kaggle)
For this small project I was trying to accurately predict the famous MNIST digit data set using CNN. Using Tensorflow and Keras, I used preprocessing, image augmentation, pooling and dropout to create a CNN that got 0.978 on the kaggle competition, Digit Recognizer, without taking very long to train. Improvements that can be made are experimenting with more augmentations, creating more layers, tuning the optimizer and going for more epochs.
![image](https://user-images.githubusercontent.com/89865352/148129154-df21ce85-e3d4-44f0-a82a-481cfc653ad5.png)

# [Project 5: Data Analysis with Python: Heart Disease](https://www.kaggle.com/arvidlevander/heartdisease)
The goal of this project was mainly to practice feature engineering in Python using some recently learned methods.
In this kernel I have used mathematical column transformations, PCA inspired column transformations and clustering using KMeans. 
The model used was XGBoost which I tuned using the Random Search Cross-validation. 
The goal of the model is to accurately predict if someone has a heart disease.
![image](https://user-images.githubusercontent.com/89865352/148130603-df4fa485-8fa0-44c8-8d62-1716a2d08610.png)

# [Project 4: Data Analysis with Python: Wine Quality](https://github.com/ArvidLev/WineQuality)
For this data analysis project I explored a wine quality dataset.
  - Used matplotlib, seaborn to perform data exploration and data visalization.
  - Binned target variable to create a classification problem instead of a regression problem
  - Used RandomForest, XGBoost and cross-validation to create a model.
  - Explored the feature importance of the models using their GINI scores
 ![image](https://user-images.githubusercontent.com/89865352/148273477-b379a907-745d-4445-b5da-a7db764046b0.png)

# [Project 3: Data Visualization with Tableau: Esport](https://public.tableau.com/views/Book1_16332383257090/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
This project I used Tableau to create dashboards for the Esports data created in project 2. I made a dashboard where you can select a team from any of the 4 big regions and then you select a specfic game of theirs and get more game specific data visualized.
![image](https://user-images.githubusercontent.com/89865352/148276393-d9f5aca3-984b-4109-b99b-f7ea286eb1a1.png)


# [Project 2: Exploratory Data Analysis with R: Esport](https://github.com/ArvidLev/LeagueOfLegends.git)
For this project I worked on data from esport games, more specifically League Of Legends esport.
Using data exploration I found variabels that I thought would be good predictors for the outcome of a game.
I used a logistic regression model and evaluated its performance and its coefficients in order to get an idea of how well the predictors were at predicting the outcome of the game.
To do this I used,
* Tidyverse to manipulate, clean and visualize the data.
* Tidymodels to analyze and train the data.
![image](https://user-images.githubusercontent.com/89865352/148274962-fbff3140-2c66-40fb-8a18-76da445aebb6.png)


# [Project 1: Data Analysis with R: Housing Prices Kaggle](https://github.com/ArvidLev/Housing_SalePrice_Kaggle)
For this project I estimated SalePrice of houses using methods from tidymodels such as rsampel, recipe, workflow, parsnip, tune and yardstick.
* Cleaned and preproccesed data by imputing, dummy variables, remove near zero variance columns.
* Used ElasticNet, MARS and RandomForest which I tuned using 5-fold crossvalidation
* Selected the best model using RMSE
![image](https://user-images.githubusercontent.com/89865352/148275547-6cebb49d-78ed-42fb-93a4-055885fc542c.png)

