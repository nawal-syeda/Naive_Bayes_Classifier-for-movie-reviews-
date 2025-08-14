# Naive_Bayes_Classifier-for-movie-reviews-
📂 Project Structure
- train/pos, train/neg: Training data organized by sentiment
- test/pos, test/neg: Testing data for evaluation
- stop_words.txt: Custom stopword list used during preprocessing
🔧 Features
- Custom Preprocessing
Cleans raw text using regular expressions and manual tokenization. Removes URLs, mentions, digits, punctuation, and stopwords — all without external libraries.
- Flexible N-gram Modeling
Supports unigram and bigram feature extraction using CountVectorizer with tunable parameters like ngram_range, max_features, and min_df.
- Naive Bayes Classifier
Includes both manual implementation and scikit-learn’s MultinomialNB. Laplace smoothing (alpha) is configurable to improve generalization.
- Benchmarking & Evaluation
Accuracy is measured on a shuffled train-test split (80/20). The pipeline supports experimentation with preprocessing, vectorization, and model parameters.
🚀 How to Run
- Prepare your dataset in the specified folder structure.
- Load and preprocess the data using the provided functions.
- Vectorize the text using CountVectorizer or TfidfVectorizer.
- Train the classifier and evaluate performance
- 🧪 Experimentation Tips
- Try different alpha values (0.1, 0.5, 1.0) to tune smoothing.
- Use ngram_range=(1, 2) to capture contextual phrases.
- Filter noisy features with min_df, max_df, and max_features.
- Compare manual Naive Bayes with scikit-learn’s implementation.


