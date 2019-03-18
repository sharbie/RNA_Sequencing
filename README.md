# RNA_Sequencing
This is the workflow for RNA sequencing analysis together with several problems shooting

# Notations of code files for this project

## This project mainly include three aspects: SIFT feature extractor, DELF extractor, CNN feature extractor.

3. CNN part includes files:
3.1 functions.py -------used to pre-process image files and batches
3.2 feature_extractor.py -------extensted with support of official CNN models (inplemented by Tensorflow). This file refereced several other people's work and was modified based on the current need by me.
3.3 save5000.ipynb This file uses feature_extractor.py to generate image features with data saving process.
3.3 Model_test.ipynb This is used for distance search including Euclidean distance, KNN, cosine similarity and also other classifiers.

