# Fake-news-detection-Comparative-Study
Official implementation of the paper : "All About Automatic Fake News Detection: A Wide Comparative Study" by Faramarz Farhangian, Rafael M. O. Cruz, Woshington V. de Souza and George D. C. Cavalcanti.

## Highlights
The contributions of this paper compared to other reviews on fake news detection are the following:
- It proposes an up-to-date taxonomy for textual-based fake news detection models and feature extraction methods.
- It presents an empirical comparison between several state-of-the-art feature extraction techniques and several classification algorithms, including transformer models used in an end-to-end model (i.e., fine-tuning) vs. as feature extractors over multiple datasets under the same experimental environment.
- It provides an error analysis regarding the possibility of combining different classifiers and/or feature extractors to increase the models’ effectiveness in predicting fake news.
- It compares different methods in the way of cost-effectiveness.
- It proposes multiple perspectives for future research based on the analysis conducted in this work.
## Organization
- A
- B
- C
- D
- E
## Requirements
To use this code, you need to have Python version 3.10 or higher. The required library can be installed by running the following command: *pip install -r requirements.txt*.

| **Library**    | **Version**   |
|:-------------: |:-------------:|
| NLTK           | 3.7           |
| Scikit-Learn   | 1.0.1         |
| Gensim         | 3.6.0         |
| Zeugma         | 0.49          |
| huggingface_hub| 0.15.1        |
| transformers   | 4.29.2        |
| xgboost        | 1.7.5         |
| wordcloud      | 1.9.2         |
| Pandas         | 2.0           |
| numpy          | 1.24.3        |
| matplotlib     | 3.7.1         |
| re             | 3.11.3        |
| tensorflow     | 2.12.0        |
| PyTorch        | 2.0           |



## Datasets
[LIAR](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip) is a collection of around 12.8k short statements manually labeled for fact-checking. The dataset was curated from PolitiFact.com and includes statements from various contexts such as news, television interviews, and radio interviews. The data was collected between 2007 and 2016. Each row in the dataset includes a news statement, a label from one of six categories (Pants-fire, False, Barely-True, Half-True, Mostly-True, True), the subject of the statement, the name and job title of the speaker, state information, party affiliation, and the context of the speech or statement.

[ISOT](https://onlineacademiccommunity.uvic.ca/isot/wp-content/uploads/sites/7295/2023/03/News-_dataset.zip) dataset consists of two CSV files containing a total of 21,417 real news articles and 23,481 fake news articles. The real news articles were sourced from Reuters.com, while the fake news articles were sourced from PolitiFact.com. The dataset covers a range of contexts, including world news and political news. Each row in the dataset includes the article title, text, type (real or fake), and publication date.

[COVID](https://competitions.codalab.org/competitions/26655) dataset was collected specifically for detecting fake news about the COVID-19 pandemic. Articles were sourced from Twitter and verified using authoritative sites like politifact.com and snopes.com. The dataset includes 10,700 entries written in English and is divided into two categories: real news and fake news.

[George McIntire (GM)](https://github.com/joolsa/fake_real_news_dataset/raw/master/fake_or_real_news.csv.zip) dataset consists of 11,000 real news articles and 3,151 fake news articles from prominent mainstream media sources such as the New York Times, Wall Street Journal, Bloomberg, and the Guardian. The articles cover a wide range of topics including politics, business, technology, entertainment, and more. Journalists have fact-checked the news articles to assign labels in the dataset.

## References
[1] W. Y. Wang, " liar, liar pants on fire": A new benchmark dataset for fake news detection, arXiv preprint arXiv:1705.00648 (2017).

[2] Ahmed H, Traore I, Saad S. “Detecting opinion spams and fake news using text classification”, Journal of Security and Privacy, Volume 1, Issue 1, Wiley, January/February 2018.

[3] Ahmed H, Traore I, Saad S. (2017) “Detection of Online Fake News Using N-Gram Analysis and Machine Learning Techniques. In: Traore I., Woungang I., Awad A. (eds) Intelligent, Secure, and Dependable Systems in Distributed and Cloud Environments. ISDDC 2017. Lecture Notes in Computer Science, vol 10618. Springer, Cham (pp. 127-138).

[4] G. McIntire, Faker ealnewsdataset/f akeorr ealnews.csv.zipatmasterjoolsa/f aker ealnewsdataset. URL https://github.com/joolsa/fake_real_news_dataset/blob/master/fake_or_real_news.1510 csv.zip.

[5] P. Patwa, S. Sharma, S. PYKL, V. Guptha, G. Kumari, M. S. Akhtar, A. Ekbal, A. Das, T. Chakraborty, Fighting an infodemic: Covid-19 fake news dataset (2020). arXiv:2011.03327.

