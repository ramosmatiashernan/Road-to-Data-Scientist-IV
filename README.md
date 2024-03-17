# Road to Data Scientist IV (NLP Problem)

Each entry in the dataset consists of a text segment representing a Twitter message and a corresponding label indicating the predominant emotion conveyed. The emotions are classified into six categories: sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5). 

A logistic regression machine learning model was implemented for sentiment analysis/emotion classification. For processing text, pretrained model BERT was used resulting in long training times. In this sense, it was used Count Vectorizer. Count Vectorizer is used to convert documents/text into vectors of term or token counts, it involves counting the number of occurences of words appears in a document. This is quite useful since it can obtain the frequency in wich words like "like", "love" or "happy" are present in texts and learn from that the relation with the emotions of the six categories.

The dataset used was provided by Nidula Elgiriyewithana, accessible at the following URL: https://www.kaggle.com/datasets/nelgiriyewithana/emotions.
