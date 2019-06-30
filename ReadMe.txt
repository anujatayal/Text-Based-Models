 ANUJA TAYAL

 Problem Statement:
 Question answering system for a text article
 
 Method of Solution
 - The application is designed to answer questions on an artical specifically Wikipedia using Gensim module of Doc2vec.
 - The application is designed in form of a chatbot which greets with hi and you can answer as many questions 
   till you thank him for his services.
 - The application scrapes the required article using Beautiful Soup, preprocesses it to remove punctuations 
   and other irrelevant texts. The processed text then trains the model using Doc2vec which converts every sentence of article to its corresponding vector. 
 - When the application is asked a question most probably a fact based question, question is preprocessed and 
   trained model calculates calculates the corresponding Doc2vec vector. 
 - And the application returns the most similar sentence from the model and also the similarity.  

 Future Improvement:
 - The Doc2vec model changes its output in every iteration 
 - The system works best for factoid questions
 - We can use biLSTM model to train the model to increase accuracy 
 - Application can be trained to output more accurately to give the required answer.
 - To increase the training set, we can use data from the embedded references.