### Sentiment Prediction Model in Film Reviews Using Natural Language Processing

An entertainment company wants to build a `machine learning` model to filter the reviews of a `movie` and categorize them. The reviews should be able to identify whether they are `positive reviews` or `negative reviews`. We will use the `dataset` of reviews from `IMDB` with `polarity labeling` to create a model that can classify `positive` and `negative` reviews. This model should have at least an `F1` score of `0.85`. We will explore the dataset using `exploratory data analysis (EDA)` to get `insights` in it and ensure that `dataset` can train the model properly. Some of the `models` with their `configurations` that we will train and test include:
- Model 0 - Constant (*Dummy Classifier*)
- Model 1 - NLTK, TF-IDF and *Logistic Regression*
- Model 2 - spaCy, TF-IDF and *Logistic Regression*
- Model 3 - spaCy, TF-IDF and LGBMClassifier
- Model 4 - BERT (*Bidirectional Encoder Representations from Transformers*) and *Logistic Regression*

| Project | Description | Library |
| ------- | ------- | ------- |
| [Sentiment Prediction Model Using NLP](https://github.com/fuadraharjo/TripleTen_ENG/blob/main/Project-12%20-%20Sentiment%20Prediction%20Model%20in%20Movie%20Reviews%20Using%20NLP/Sentiment%20prediction%20model%20in%20film%20reviews%20using%20natural%20language%20processing.ipynb) | The sentiment prediction model uses *natural language processing* on `machine learning` models. Tokenization and lematization is done using *spaCy*, *nltk*, and *BERT* modules. Some of the `models` tested are `dummy classifier`, `logistic regression` and `lightGBM`. | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *math*, *re*, *tqdm*, *nltk*, *spaCy*, *LightGBM*, *torch*, *transformers* |