# Analysis & Classification of Hoax in MAFINDO Dataset

## Set
- **Dataset:** Hoax dataset obtained from [MAFINDO (Masyarakat Anti Fitnah Indonesia)](https://raw.githubusercontent.com/taudataanalytics/taudata-Academy/master/data/Data-Hoax-Mafindo.csv);
- **Slang:** Modified Kamus Alay based on [Kamus Alay (Colloquial Indonesian Lexicon)](https://github.com/nasalsabila/kamus-alay);
- **Feature Extraction:** `Bag-of-Words`, `TF-IDF`;
- **Classifier:** `Naive Bayes`, `SVM`, `Logistic Regression`, `Decision Tree`, `kNN`, `ANN`.
- **Cross-Validation:** `GridSearch`, `RandomSearch`

This dataset contained two label values, namely "1" for hoax and "0" for not hoax. The total data in this dataset is 4,701. Each label has a varied amount of data distribution, including 3850 data for hoax and 851 data for not hoax.

| **Label**      | Hoax |  Not Hoax   |
| :------------- | :--: | :---------: |
| **Total Data** | 3850 |     851     |
