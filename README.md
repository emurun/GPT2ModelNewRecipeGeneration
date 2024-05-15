# GPT2ModelNewRecipeGeneration
In today’s busy world, people have hard time choosing what to cook for themselves everyday. To solve this problem, we recommend a chat-style Personalized Recommer Recipe System which interacts with a user and recommends a new recipe based on their dietary restrictions and taste preferences. 
This is an intelligent agent which uses natural language processing (NLP) techniques to understand a user through text conversation. Based on the user’s preferences, the personalized recommender system would use Food.com Dataset to recommend new recipe to try. 

The model is using GPT-2 transformer and is fine-tuned on custom Food.com dataset. This dataset has around 450,000 recipes. This model used Retrieval Augment Generation (RAG) with guardrails to ensure the safety of a new recipe. As part of the RAG implementation, the model uses 70% of the dataset as a knowledge base to retrieve relevant recipes with certain ingredients. This ensure up-to-date and reliable informtion and improves response quality which leads to an efficient knowledge retrieval. 

RAG with Guardrails retrieves top 5 recipes with your given ingredients and feeds that informaiton into the fine-tuned GPT-2 model. 

Run demo.ipynb Jupyter Notebook to generate new recipe based on the ingredients you have at hand! 


