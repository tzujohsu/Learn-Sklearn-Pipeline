### About Sklearn pipeline

I followed sklearn pipeline turtorials and explored more on chaining different steps together. 

Pipeline allows us to sequentially apply a list of transformers to preprocess the data and conclude the sequence with a final predictor for predictive modeling. It assembles several steps that can be cross-validated together, avoiding potential data leakage issues.

These are the examples I have goney through in the notebook.
1. Digit Classification: PCA -> Logistic Regression
2. Digit Classification: Scaling -> Dimension Reduction -> Linear SVC(SVM)
3. Toxic Comment Classification: Lemmatizer -> TFIDFs -> NBFeaturer -> Logistic Regression
4. Document NewsGroup Classification: TfidfVectorizer -> ComplementNB
