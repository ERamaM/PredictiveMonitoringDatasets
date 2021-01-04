# Datasets for "Deep Learning for Predictive Business Process Monitoring: Review and Benchmark"

This repository contains the datasets used for the experimentation of the paper "Deep Learning for Predictive Business Process Monitoring: Review and Benchmark". Two different sets of logs are provided:

- "raw_datasets": contains the XES converted datasets directly extracted from [4TU.ResearchData](data.4tu.nl).
- "split_datasets": contains the XES 64/16/20 ordered splits of the original datasets. The prefix of the file indicates to which split it belongs:
  - "train_": Training set, i.e, the first 64% of the log.
  - "val_": Validation set, i.e, the 16% of the log after the training set.
  - "test_": Test set, i.e, the 20% of the log after the validation set.
  - "train_val_": Training and validation set together, i.e, the first 80% of the log.
