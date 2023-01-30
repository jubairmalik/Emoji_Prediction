# Prediction of Emojis from Tweets


Emojis play an important role in textual communication nowadays. As emojis are short and easy to send, the usage of emojis is increasing rapidly and it is changing the way of communication in our everyday life. So, if anyone tries to model social media communication, they have to consider the way of dealing with emojis. Finding an effective way of predicting the emoji associated with a piece of content may help to improve different NLP tasks such as information retrieval, suggestion of emojis when writing text messages or sharing pictures online . We can also improve in the field of sentiment analysis, emotion recognition and irony detection by modeling the semantics of emojis. In this project, we propose a new model to predict the most likely associated emoji in English tweets based on BERT. We got our highest accuracy with a BERT-base of 0.35 and macro f1 score 0.23 and we have got 7 emojis with the highest number of f1 scores which constitutes 29.2% of the testing dataset.

__Mapping of Emojis__

![Mapping of Emojis](https://user-images.githubusercontent.com/63742110/215383721-cf329005-3948-4254-a3e7-7aaf2f8e3adf.png)

__Architecture of our model__

![Architecture](https://user-images.githubusercontent.com/63742110/215383724-8d164bce-0b81-4a4d-ab38-d60467d295fd.png)

__Result of our model__

Now we are comparing our result with the other teams that have achieved the highest macro f1 score for each class. We can see from table that we are achieving a greater or equal to f1 score for seven individual emojis (Bold red color)

![Screen Shot 2023-01-29 at 9 49 26 PM](https://user-images.githubusercontent.com/63742110/215383770-a6895a62-e51e-4685-b0dd-e7b6de67859b.png)
