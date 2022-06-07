                                              SENTIMENT Classification using BERT
 
 Problem Statement -
 
 In this project we will be building a sentiment classifier using the bert pretrained model. The dataset we will be using will be IMDB movie reviews dataset.
 
 Description Overview -
 
The process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral. Understanding people’s emotions is essential for businesses since customers are able to express their thoughts and feelings more openly than ever before. By automatically analyzing customer feedback, from survey responses to social media conversations, brands are able to listen attentively to their customers, and tailor products and services to meet their needs.
Sentiment analysis, however, helps businesses make sense of all this unstructured text by automatically tagging it. Sentiment analysis uses various Natural Language Processing (NLP) methods and algorithms, which we’ll go over in more detail in this section.

The main types of algorithms used include:

1. Rule-based systems that perform sentiment analysis based on a set of manually crafted rules.

2. Automatic systems that rely on machine learning techniques to learn from data.

3. Hybrid systems that combine both rule-based and automatic approaches.

Sentiment analysis can be used for varous applications -
1. Social media monitoring

2. Brand monitoring

3. Voice of customer (VoC)

4. Customer service
 
 
 Technology Used -
 
 Python 3.6,Pytorch 1.4 with GPU support 
 
 Installation of the Project -
 
 The installation of the project is easy.Please do follow the steps to create a virtual environment(good pratice while creating a new project) and then install the    necessary packages in the environment
 
 In PyCharm it's easy
 
 STEPS:-
 1. Create a New Project 
 2. Navigate to the directory of the project
 3. Select the option to create a new virtual environment using conda with python 3.6
 4. Finally create the project using used resources
 5. After the project has been created,install the necessary packages from requirements.txt fule using the command
 
 pip install -r requirements.txt
 
 In Conda also it's easy
 
 STEPS:-
 1. Create a new virtual environment using the command 
 
 conda create -n your_env_name python=3.6
 
 2. Navigate to the project directory
 3. Install the necessary packages from requirements.txt file using the command 
 
 pip install -r requirements.txt
 
 Workflow Diagram -
 
 ![image](https://user-images.githubusercontent.com/61505882/172435600-4c66b841-d550-411e-bee9-065f97ccfff3.png)

Implemenatation -

1. Project Directory

![image](https://user-images.githubusercontent.com/61505882/172437470-8b2bf08d-c7a0-4d4c-9e5f-53f607a61f5f.png)

This is the folder structure of the project

models - This folder will keep the model that have been trained on the dataset using BERT Architecture.

2. requirements.txt

![image](https://user-images.githubusercontent.com/61505882/172438021-1afcaa7f-e206-4d3c-ab5f-a16b55b48d2f.png)

3. clientApp.py

![image](https://user-images.githubusercontent.com/61505882/172438292-915259d9-e22d-4d03-9cd3-ef8decff8884.png)

This is the flask server file and entry point of application

4. predictionFile.py

![image](https://user-images.githubusercontent.com/61505882/172438802-72f4adb5-8c30-4294-93be-6fed6c07019c.png)

Testing in Local/API - 

To run this project in your local system just run the file clientApp.py and after that web server will start at localhost 7001 port

![image](https://user-images.githubusercontent.com/61505882/172439360-d7e7d3a9-cd8e-4355-aa64-77562f4b2d27.png)

Enter the review or reviews to predict

![image](https://user-images.githubusercontent.com/61505882/172440269-5031d363-aefa-4552-9fe3-589b4be9dfea.png)

Conclusion -

Here we successfully performed sentiment analysis and analysed the reviews on the given dataset

Improvements -

More data or better larger dataset can be used to build a better model.We can try out better pre-trained model with fine tuning to improve the performance










