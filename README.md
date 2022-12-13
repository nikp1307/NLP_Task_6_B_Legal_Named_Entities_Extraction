# NLP Task 6B: Legal Named Entities Extraction

The Judicial System in various countries have a lot of pending cases at their end due to the increase in crimes and illegal activities around the world and these cases have been increasing substantially. Natural Language Processing techniques like Named Entity Recognition can be used to automate some of the intermediate tasks in the judicial pipeline.

In this task, we have used a transformer based NER model called the Distil-Roberta model using an NLP library called SpaCy. Distil Roberta base model is a type of natural language processing (NLP) model based on the RoBERTa (Robustly Optimized BERT Pretraining Approach) architecture. RoBERTa is a type of BERT (Bidirectional Encoder Representations from Transformers) model, which is a type of transformer-based neural network that has been pre-trained on a large amount of text data.

The dataset list consists of various keys such as id, annotations, data, and meta. From this, we only need data and annotations keys. And then we create a new list consisting of these needed keys. For training our model using a training dataset, we have used a transformer-based NER model called distilroberta-base to identify legal entities from legal text. To implement this NER model, we have used the sPaCy library and transformers in this library. For quantitative analysis, we have evaluated the accuracy for this model. For qualitative analysis, we have highlighted legal entities in the legal text present in the DEV dataset.

The training model achevied an F1 score of 0.98 when we ran it against Judgment dataset. The training scores can be seen as below:

![alt text](https://github.com/nikp1307/NLP_Task_6_B_Legal_Named_Entities_Extraction/blob/main/Judgement.png)


The training model achevied an F1 score of 0.97 when we ran it against Preamble dataset. The training scores can be seen as below:

![alt text](https://github.com/nikp1307/NLP_Task_6_B_Legal_Named_Entities_Extraction/blob/main/Preamble.png)
