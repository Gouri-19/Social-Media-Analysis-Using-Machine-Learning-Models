# Social-Media-Analysis-Using-Machine-Learning-Models

Social media, which is extensively used across the world, plays an important part in the everyday lives of the majority of people. Individuals can use social media platforms to discover and learn new information, exchange ideas, and engage with new individuals and organizations. It has transformed the way people live today and made communication much easier. It facilitates the sharing of user-generated material such as data, images, and videos. From social media sites, there is a wide range of high-speed, high-volume data generated on a daily basis. Greater accessibility of internet connections, improved software tools, sturdy PCs, and mobile devices may all be credited with the increasing availability and use of social media. Today, social media platforms such as Facebook, Twitter, Instagram and WhatsApp have millions of users and have had a significant influence on people's lives. Not only have people shared photos and information, but trades and businesses have thrived as well. Businesses use social media to reach their potential customers easily. Furthermore, it is mostly utilized by educators and students which helps in contributing a lot for teaching and learning purposes.

The project aims to predict a person's overall social media consumption based on how much time they spend on social media sites like Whatsapp, Instagram, and Facebook. The algorithm will forecast if a user has a high or low engagement activity level based on their Instagram followers and amount of posts.The main purpose of our project is to predict the total social media usage of a particular individual based on the time spent on social media in various platforms such as whatsapp, instagram and facebook. Our aim is to predict which platform is being used the most by an individual based on time spent on weekends versus time spent on week-days. Using instagram followers and number of posts, the algorithm will predict whether the user has a high or low interaction activity status.

# Methodology adapted:
● The data was collected from the Kaggle website. The dataset was called Social Media Usage analytics.
● Then the data-preprocessing starts.
● The data set we used, we first checked for the presence of any null values. Our data set did not include any null values.
● The column names were renamed for convenience
● Unwanted or irrelevant columns which had practically 0 contribution to our prediction were dropped.
● The numerical and string data types were in object format and we had to convert them into string and int data types respectively because mathematical functions cannot be applied to object data types.
● The last but the most important part of the preprocessing was converting string numeric values to integer values. Columns such as “Total Instagram Usage ” had values stored as a string so we had to process it by removing the ‘,’ and then converting it from Object to String and then finally to Integer.
● We also performed a few basic visualizations on the dataset.
● Machine Learning models used are; Random Forest, Linear Regression and XGBoost.
● Linear regression model was used to predict the total social media usage based on the time spent on each platform “last week”. The train:test ratio was 70:30.
● We used cross- validation to overcome the overfitting issue in the model.
● Linear Regression model was used to predict the total social media usage based on the time spent on each platform “last weekend”. The train:test ratio was 70:30.
● XGBoost model is used to improve the performance for total social media usage in the last week for all three platforms. The train:test ratio was 70:30.
● Random Forest model was used to predict which platform is used the most by an individual based on the time spent on week and time spent on weekends. The test size
used is 25 percent.
● Linear regression model was used to predict the activity status of an individual based on number of instagram posts and number of instagram followers.
● Finally, model evaluation such as the mean absolute error, r-square score, mean standard error, the coefficient matrix and model visualization was performed for the models used.

