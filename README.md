# Sarcasm-Detection

Sarcasm, a sharp and ironic utterance designed to cut or to cause pain, is often used to express strong emotions, such as contempt, mockery or bitterness. Sarcasm detection is of great importance in understanding people’s true sentiments and opinions. Application of sarcasm detection can benefit many areas of interest of NLP applications, including marketing research, opinion mining and information categorization. However, sarcasm detection is also a very difficult task, as it’s largely dependent on context, prior knowledge and the tone in which the sentence was spoken or written.

In this project, I aim to answer the question if sarcastic sentences can be identified automatically using the following ML/DL technique :
- Random Forest
- Naive Bayes Theorem
- Support Vector Machines
- K-Nearest Neighbors
- BERT
 
## Requirements
The project makes use of the following libraries
- numPy
- pandas
- nltk
- plotly
- sklearn
- transformers

## Dataset
I use the news-headlines-dataset which is available to download at Kaggle Dataset  [here](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection) . In this dataset, each record consists of three attributes:

- is_sarcastic: 1 if the record is sarcastic otherwise 0
- headline: the headline of the news article
- article_link: link to the original news article. 

## Performance
The final model performance in terms of accuracy can be found in the table below:

| Model              | AUROC |
|--------------------|-------|
| Random Forest      | 0.95  |
| Naive Bayes        | 0.76  |
| SVM                | 1.0   |
| K-Nearest Neighbor | 0.97  |
| BERT               | 0.95  |

## Acknowledgements
- Thanks to [Rishabhmisra](https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection) for this dataset as well as his below research.
  + Misra, R., & Grover, J. (2021). Sculpting Data for ML: The first act of Machine Learning.
  + Misra, R., & Arora, P. (2019). Sarcasm detection using hybrid neural network. arXiv preprint arXiv:1908.07414.
