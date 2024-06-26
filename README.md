# PBPMCD
PBPMCD : Detecting sudden and gradual drifts based on predictive business process monitoring

# Requirements
```
lxml==5.2.0
matplotlib==3.8.3
numpy==1.19.5
pandas==2.2.1
scikit_learn==1.4.1.post1
torch==1.6.0+cu101
torch_geometric==2.5.2
tqdm==4.66.2
```

You can install the requirements using `pip install -r requirements.txt`

## Datasets
You can download dataset in https://data.4tu.nl/articles/dataset/Business_Process_Drift/12712436.

## Preprocessing dataset
You can transfer XES,and MXML format event log into csv format by running 1.data_transfer.ipynb.

## Next activity prediction dataset generating
You can split event log into some fixed size sub-logs and generate next activity prediction datasets by running 2.data_split_and_prefix_generating.ipynb.

## Drift detection
You can run 3.model_train.ipynb to train prediction and start detect concept drift.

