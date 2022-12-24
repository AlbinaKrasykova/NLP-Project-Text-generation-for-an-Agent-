# NLP-Project-AI chatbot(Agent WorkFlow automatization)-

![](https://github.com/AlbinaKrasykova/NLP-Project-Text-generation-for-an-Agent-/blob/main/AI.png) 

The goal of the NLP AI chatBot project is to develop 
a NLP machine learning model
that suggests words and phrases to an agent 



Business Impact

Improve time needed for response generation
Improve customer experience
Lessen burden on agents when replying to customers

I was working independently under supervision of ASAPP advisor Heather Reed to develop an efficient solution for Agent workflow Optimization.
To make the workflow more efficient, and less costly: I decided to divide the project on 2 main parts:
# Part #1 – consisted of the pipeline for clusters production for 2 separate cvs files (clusters for agent and clusters for a customer which contained)
![](https://github.com/AlbinaKrasykova/NLP-Project-Text-generation-for-an-Agent-/blob/main/Demo%20part%201%20agent%20automation.gif)
# Part #2 – creating a new data frame with the most relevant features and building model, getting predictions
![](https://github.com/AlbinaKrasykova/NLP-Project-Text-generation-for-an-Agent-/blob/main/Demo%20part%202%20agent%20automation%20solution.gif)
And picking most relevant sentences based on cosine similarity.   

-	Data Analysis of synthetic developed 10K Dataset (Agent & Customer dialogue)
-	Feature Engineering (as extracting exactly 1 customer and agent text from the text)
-	Data cleaning and preprocessing for Kmeans clustering (as text cleaning, applying TFIDF vectorizer, I was producing 2 cvs files with clusters for customer and agent text separately)
-	Second of the project is about building a model for text prediction. (As my feature I used customer clusters and for my label to predict I used agent clusters. I tired 3 different models as 
-	Random Forest, Naive Bayes and Logistic regression.)
-	After I got my predictions, I used cosine similarity to get the most relevant and closest to the actual customer sentence – a three options for an agent to choose.) 
Further steps to improvement: adding more relevant features using a correlation matrix, working with 


