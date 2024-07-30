# Depression: Twitter Dataset - Feature Extraction

This repository contains a notebook for feature extraction from the ["Depression: Twitter Dataset + Feature Extraction"](https://www.kaggle.com/datasets/infamouscoder/mental-health-social-media/data) dataset. 
The notebook preprocesses the text data and extracts features that can be used for further analysis or machine learning tasks.

## Dataset Description

The dataset contains the following columns:

- **post_id**: Post ID of the post
- **post_created**: Date and time when the post was created
- **post_text**: Uncleaned tweet text
- **user_id**: User identification number
- **followers**: Number of followers the user has
- **friends**: Number of friends the user has
- **favourites**: Number of favourites the user has
- **statuses**: Total status count of the user
- **retweets**: Total retweets on the post

## Notebook Overview

The notebook performs the following steps:

1. **Loading the Dataset**: Loads the dataset into a pandas DataFrame.
2. **Exploring the Dataset**: Provides a summary of the dataset, including checking for missing values.
3. **Preprocessing the Data**: Cleans the text data by removing URLs, mentions, hashtags, numbers, punctuation, and stopwords.
4. **Feature Extraction**: Extracts text-based features using TF-IDF and combines them with user-based features.
5. **Saving the Extracted Features**: Saves the extracted features to a file for future use.

## Dependencies

The notebook requires the following Python packages:

- pandas
- numpy
- scikit-learn
- nltk
- re
- jupyter

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset is sourced from [Kaggle](https://www.kaggle.com/).
