# NLP_emotion_classification


## Team Members: 

Jason Huang, Mark Li, Daniel Wang, Wesley Wang, Gabriel Zhang

## Topic:

Social media emotion classification

## Business Problem:

In social media platforms such as Twitter, there are many posts with different emotions, being able to identify the emotion from user’s posts, we can 
can help with the following aspects:

Personalized Content: Help to make personalized advertisements or contents based on users’ emotions.

Mental Health Support: Detect early signs of mental health issues such as depression, anxiety, or stress by identifying patterns of sadness, fear, or anger in users' posts.

Content Regulation: Content inspectors can prioritize the review of content with extreme emotions or the user with frequent negative emotional posts.

So our business problem is that if we can tell the emotion from the content of users’ posts and categorize them into six basic emotions.

## Methodology

### Logistic classifier

### Random Forest Classifier

### Pre-trained Language Model (bhadresh-savani/bert-base-uncased-emotion)

### Fine-tuned BERT (bert-base-cased)

## Result



## Dataset:

Source: [dair-ai/emotion · Datasets at Hugging Face](https://huggingface.co/datasets/dair-ai/emotion)

## Dataset Description:

The dataset is a collection of English Twitter messages (about 20k records), each labeled with one of six basic emotions: anger, fear, joy, love, sadness, and surprise. We intend to use this dataset for sentiment analysis or emotion recognition tasks.

Each entry in the dataset consists of two fields:
Text: This field contains the raw text of a Twitter message. The text is likely to be informal, with the use of internet slang, abbreviations, and possibly emojis, given the nature of Twitter as a social media platform. The messages might vary in length, with most tweets being on the shorter side, but with some extending to longer lengths.

Label: The label field corresponds to the emotion that is associated with the text of the Twitter message. The six emotions are encoded as integers ranging from 0 to 5, where each number corresponds to a specific emotion. 

## Reference

```
@inproceedings{saravia-etal-2018-carer,
    title = "{CARER}: Contextualized Affect Representations for Emotion Recognition",
    author = "Saravia, Elvis  and
      Liu, Hsien-Chi Toby  and
      Huang, Yen-Hao  and
      Wu, Junlin  and
      Chen, Yi-Shin",
    booktitle = "Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing",
    month = oct # "-" # nov,
    year = "2018",
    address = "Brussels, Belgium",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D18-1404",
    doi = "10.18653/v1/D18-1404",
    pages = "3687--3697",
    abstract = "Emotions are expressed in nuanced ways, which varies by collective or individual experiences, knowledge, and beliefs. Therefore, to understand emotion, as conveyed through text, a robust mechanism capable of capturing and modeling different linguistic nuances and phenomena is needed. We propose a semi-supervised, graph-based algorithm to produce rich structural descriptors which serve as the building blocks for constructing contextualized affect representations from text. The pattern-based representations are further enriched with word embeddings and evaluated through several emotion recognition tasks. Our experimental results demonstrate that the proposed method outperforms state-of-the-art techniques on emotion recognition tasks.",
}
```


