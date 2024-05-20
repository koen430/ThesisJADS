The code in this repo is used in the order shown by their filenames. For clarification find the following:

1-Preprocessing is used to load the data from huggingface and preprocess it for the purposes of this thesis. It stores the datasets.

2-Selection is used to select the relevant datapoints for the following steps in the pipeline from the previous stored data and stores the new datasets in train-val-test splits.

3-News_raining and 3-Twitter_training are used to train Phi2 on both finalized datasets. It stores the models and the logs of the training.

4-Logging is used to visualize the logs of the training for the models from the stored logs.

5-GPT_test, 5-Phi_test, 5-Phi_q_test are used to generate the results with the trained and GPT models. The results are stored.

6-Scoring is used to retrieve the metrics for the responses, the confusion matrices are stored.

7-Data_upload_to_HF, 7-Model_upload_to_HF is used to upload the final versions of the data and models to HuggingFace.

