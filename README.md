Predicting Rental Price of Lane Houses in Shanghai with Machine Learning Methods and Large Language Models

Authors:

Tingting Chen(18790061936@163.com)

Shijing Si(shijing.si@shisu.edu.cn)

#Link to source paper for citation:

https://arxiv.org/abs/2405.17505

###########################################

In order to run the code make sure you pre-instal all the dependecies such as sklearn.

1.Preprocessed File:for_tableau_2.csv

2.Further data cleaning and modeling of five machine learning models:上海租金估计---机器学习.ipynb

3.Large Language Models prompt:

Each piece of training data we enter is described as follows.

"The property is located in [Location], and it is a [house type] with an area of [area] square feet. It features [number] bedrooms, [number] living rooms, and [number] bathrooms, along with amenities such as [air conditioner, heat, outdoorspace]. "(specific data can be referred to rentaltext.csv)

For 0-shot, it means that the LLM is asked to predict house prices based solely on the provided prompts without any prior training data.

For 1-shot, it means that each prediction is based on one training data point, selected to be as similar as possible to the test data in terms of location, house type, and other features.

......

Calculating the mse, mae and R-squared values of each time.

  4.Drawing comparison diagrams of the results of LLMS:chatgpt大语言模型（绘图）.ipynb

