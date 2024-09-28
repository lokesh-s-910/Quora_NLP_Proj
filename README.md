# Quora_NLP_Proj
The goal of this competition is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case-by-case basis for individual items in the dataset.
# Quora Dataset 4Lakhs Record Were Given 
  - Randomly 30k Samples were took reduce computational complexity
  - Data Preprocessing were Tokenization, StopWord_Removal, Punctuation Handling, Lemmatization
  - Feature Extraction
      - BagOfWords were applied which produced low accuracy
      - Tf_Idf_Vectorizer applied to Improve Accuracy
      - Better Improvement in Model Word2Vec could be applied to reduce computational complexity
  - I applied the Random Forest given Model which gave me a 79% accuracy score which gave the result of similar latent value
