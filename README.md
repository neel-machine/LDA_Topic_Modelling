# Topic Modelling

This project uses the scraped appstore reviews and applies LDA (Latent Dirichlet Allocation) model to assign topics to each review. The end goal of this project is to solve the problem of identifying actionable insights from rreviews on which app developers can work on. Out of undreds of reviews the Doordash app gets everyday developers can benefit from this model that can segregate reviews that are specific to problems in the app

For example these are the two reviews taken from Doordash playstore reviews page

<img width="684" alt="Screenshot 2023-05-17 at 11 33 01 AM" src="https://github.com/neel-machine/LDA_Topic_Modelling/assets/114842914/73b70b7c-113a-46b3-ad4c-2dce87838399">









<img width="669" alt="image" src="https://github.com/neel-machine/LDA_Topic_Modelling/assets/114842914/15404dba-48f9-458f-85e8-2118f55b9f92">


Topic modelling would mark each review accordingly , in this project the ideal number of topics we selected was 4, namely  Account related issues, delivery related issues , app related issues and others . For implementation I have used Gensim , NLTK and Spacy libraries to remove stopwords, lemmatization and tokenisation. To get a birds eye view of the processed text created a wordcloud for better visualisation.

![image](https://github.com/neel-machine/LDA_Topic_Modelling/assets/114842914/6e470948-052f-4820-92fd-2d66d4d43953)

