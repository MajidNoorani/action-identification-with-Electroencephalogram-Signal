# Action Identification on Electroencephalogram Signal

Making data classification on [Synchronized Brainwave Dataset](https://www.kaggle.com/datasets/berkeley-biosense/synchronized-brainwave-dataset/data)

the classification has been made using Convolutional neural networks and the model specification is as follows:
1. 6 Convolutional layers (followed by batch normalization layers)
2. 4 dense layers (followed by dropout layers)
3. Total params: 48989135 (186.88 MB)

# Data
The data has 67 labels but we have reduced them to 15 categories
8958 samples for training
996 samples for validation

# Metrics
 - TopKCategoricalAccuracy(k=3)
 - F1Score(average='micro')
 - AUC()
 - metrics.Precision()
 - metrics.Recall()



