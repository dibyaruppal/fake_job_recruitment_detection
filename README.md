#  Fake Job Recruitment Detection 


This repository provides a novel approach to online recruitment fraud detection by integrating various Natural Language Processing concept for capturing intregate features of the the post and provide accurate solution. Processing online fake recruitment posts is a complex task that requires a deep understanding of textual information to accuratly identify the fake and guenine posts. The proposed model leverages the strengths of BERT in natural language processing.

## Brief Description
- Fraud people can scam job seekers from online recruitment by posting Fake Jobs to steal Job seekers' money is known as an Employment scam.
- Employment scams are one of the serious issues in recent times addressed in the domain of Online Recruitment Frauds (ORF)
- In 2012, the Australian Bureau of Statistics published a report about personal fraud stating that 6 million people per year were exposed to several forms of scams including employment scams.


##  Importance of the problem
- Fraudulent job advertisements can be posted against a reputed company for violating its credibility and damaging its reputation.
- Innocent people many times become victims of this scam their money and personal information come at stake.

## Data
**Employment Scam Aegean Dataset (EMSCAD)**
 Legitimate Samples : 17014
 Fraudulent Samples : 866
 Total Samples      : 17880
![image](https://github.com/user-attachments/assets/8a00665d-bc1d-4195-949b-27b9280a15e3)

- **Reference :** [Recruitment Scam - kaggle Dataset](https://www.kaggle.com/datasets/amruthjithrajvr/recruitment-scam)

## Tech Stack

- **Preprocess text** 
    - NLTK / spaCy / gensim
- **Dataframe and computation**
    - Pandas / Numpy
 - **Visualization of the dataset** 
    - Matplotlib / seaborn / WordCloud
 - **Models** 
    - Sklearn, PyTorch, TensorFlow, transformer

## NLP Techiques used
1. **Text Preprocessing**
    - Removal of punctuation, special characters, emojis etc.
    - Stemming
    - Shallow Parsing
    - Dependency Parsing
    - Named Entity Recognition(NER) tagging
    - Principal Component Analysis(PCA) 
2. **Vectorisation techniques**
    - TFIDF
    - word2vec
    - BERT embedding
    - RoBERTa embedding
    - distilBERT embedding
3. **Models**
    - Logistic Regression
    - kNN classfier
    - Random Forest classfier
    - Adaboost classfier
    - Multi-layer perceptron
    - Bidirection-GRU

## Result

The best result is achieved using BERT embeddings and followed by classification using Neural Network.
![accuracy_scores](https://github.com/user-attachments/assets/deae88c1-731f-4453-932b-aac1d5ab5b48)


## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Make sure to include tests if you are adding new functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or suggestions, please open an issue in the repository or contact the project maintainer at [Dibyarup Pal](mailto:dibyarup.pal@iiitb.ac.in).

---

Thank you for using the fake job recruitment detection solution for Online Recruitment Frauds(ORF). I hope you find it useful and easy to use!
