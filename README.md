# Notations of code files for this project

## This project mainly include three aspects: SIFT feature extractor, DELF extractor, CNN feature extractor.
1. SIFT part and DELF
  - pipeline.py Pipeline complete implementation, generating histogram and image vector matrix for SIFT
  - retrieve_img.py main function for image retrieval
  - compute_map.py Prepare query set
  - convert for eval.py Dataset preparation
2. CNN part includes files:
  - functions.py -------used to pre-process image files and batches
  - feature_extractor.py -------extensted with support of official CNN models (inplemented by Tensorflow). This file refereced several other people's work and was modified based on the current need by me.
  - save5000.ipynb This file uses feature_extractor.py to generate image features with data saving process.
  - Model_test.ipynb This is used for distance search including Euclidean distance, KNN, cosine similarity and also other classifiers.

