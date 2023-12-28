# Toxic-Comment-Analysis-for-Online-Learning

Third-year project in Computer Science and Engineering (Intelligent Systems) at MIT School of Engineering, MIT ADT University.

**Publication at IEEE ACCESS'21 :** https://ieeexplore.ieee.org/document/9563344  

**Abstract:**

Due to recent circumstances of the pandemic, online platforms are becoming more and more essential for communication in many sectors. But because of this, a lot of negativity and toxic comments are surfacing, resulting in degradation and online abuse. Educational systems and Institutions heavily rely on such platforms for e-learning leading to unrestricted attacks of toxic and negative comments towards teachers and students. Due to this work, issues of constant bullying and online abuse will be reduced. The comments classified are according to the parameters from our self-prepared dataset combined with Kaggle's toxic comment dataset, named as toxic, severely toxic, obscene, threat, insult, and identity hate. Machine Learning algorithms such as Logistic Regression, Random Forest, and Multinomial Naive Bayes are used. For data evaluation, ROC and Hamming scores are used. The output will be shown as the rate of each category in percentile and in a graphical format. This work will help reduce the online bullying and harassment faced by teachers and students and help create a non-toxic learning environment. In this way, the main focus will be on studying and not getting de-motivated and discouraged by hateful comments and people commenting toxic comments will also get reduced.

**Algorithms Used:**
1. Logistic Regression
2. Random Forest
3. Multinomial Naive Bayes
4. NLP Techniques (lemmatization, lexicon normalization, and TF-IDF algorithm)

**Flowchart:**

![image](https://github.com/Manaswi-Vichare/Toxic-Comment-Analysis-for-Online-Learning/assets/83514527/ff2ba4f2-ce87-4a83-896d-89f5ec78a8e7)

**Results:**

![image](https://github.com/Manaswi-Vichare/Toxic-Comment-Analysis-for-Online-Learning/assets/83514527/cd6a109c-436e-4b78-ac01-bd8b398c8e0b)

**ROC Curves:**

![image](https://github.com/Manaswi-Vichare/Toxic-Comment-Analysis-for-Online-Learning/assets/83514527/bd46c098-86c7-452f-b968-6b186022ae7c) ![image](https://github.com/Manaswi-Vichare/Toxic-Comment-Analysis-for-Online-Learning/assets/83514527/3402cd25-128e-492a-8ca9-c20c83a6ee5c)
![image](https://github.com/Manaswi-Vichare/Toxic-Comment-Analysis-for-Online-Learning/assets/83514527/495c2737-1a04-4181-9ec2-e262f7701f94)

**Conclusion:**

In this paper, three models for toxic comment classification are proposed, which are: Logistic regression model, Multinomial Naive Bayes, and Random Forest. The models are used to classify the toxic comments as toxic, severely toxic, insult, threat, obscene, and identity hate. By data collection and preprocessing to classify toxic comments with the help of lemmatization, lexicon normalization, and TF-IDF algorithm, we train and test the models and evaluate using ROC curves and hamming score. Based on the obtained results, we can conclude that the most effective is the Logistic regression model, which provides the best accuracy: 0.92 when testing on a training data set. As a future scope, a better and faster model in place of Random Forest can be implemented. We can implement deep learning models to obtain a much higher accuracy rate. 
