# DeepLearning_NN.ipynb

Overview
--------
This Jupyter Notebook demonstrates basic deep learning workflows using TensorFlow/Keras and scikit-learn. It contains two main parts:

- Regression: a feed-forward neural network for predicting house prices using `bengaluru_house_prices.csv`.
- Classification: a feed-forward neural network for customer churn prediction using `Churn_Modelling.csv`.

Files
-----
- DeepLearning_NN.ipynb — the notebook (this file).
- data/bengaluru_house_prices.csv — dataset used in the regression section.
- data/Churn_Modelling.csv — dataset used in the classification section.

Files location
--------------
- Notebook file: [DL/DeepLearning_NN.ipynb](DL/DeepLearning_NN.ipynb#L1)
- Datasets: [DL/data](DL/data)

-----------------------------------------------------------------

# cnn.ipynb

Overview
--------
`cnn.ipynb` is a PyTorch-based notebook demonstrating an end-to-end image classification workflow on a weather dataset (Kaggle). The notebook covers:

- Dataset exploration and class distribution visualization
- Train / validation / test splitting with reproducible seed
- Image preprocessing and augmentation using `torchvision.transforms`
- A simple custom CNN implemented in `torch.nn`
- Transfer learning with EfficientNet (pretrained weights) and fine-tuning
- Training loops, evaluation metrics, confusion matrix, and sample predictions

Dataset
-------
The notebook references a Kaggle dataset in the original source. If you downloaded the dataset, set the notebook variable `DATASET_PATH` to the local folder that contains class subfolders (one folder per class).

Original references in the notebook:
- Kaggle notebook: https://www.kaggle.com/code/mennaabdelbaky/cnn-ipynb
- Dataset: https://www.kaggle.com/datasets/jehanbhathena/weather-dataset

Files
-----
- cnn.ipynb — the notebook
