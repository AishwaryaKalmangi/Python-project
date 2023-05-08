TITLE: BBC NEWS CLASSIFICATION USING DIFFERENT ALGORITHMS

1.The first stage is the Dataset Preparation step, which entails loading a dataset and carrying out fundamental pre-processing.
• Mount the google drive to use the file from drive.

• Load the BBC News dataset which can be downloaded from Kaggle.

• Download dataset: https://www.kaggle.com/datasets/yufengdev/bbc-fulltext-and-category

• Read the data, we can see categories v/s Text(article headline text).

• Remove unnecessary columns.

• Count unique categories & text for each.

• Visualize the count of articles for each category.

• Remove duplicate rows.

• Find word cloud, most frequent words from ‘text’ column.

• Pre-processing & Tokenization is performed in this step mainly.

2.The following stage is feature engineering, which involves turning the raw dataset into flat features that can be incorporated into a machine learning model. The process of extracting new features from the existing data is also a part of this step. Following that, the dataset is split into train and validation sets. • Converting text into appropriate features is the first step.
• Count Vectors as features.

• TF-IDF Vectors as features.

• Split the dataset into Train & Test datasets.
