# Medium Articles Dataset Generator

This project combines multiple datasets from Kaggle and Hugging Face to create a comprehensive collection of Medium articles. The combined dataset is available on [Hugging Face Hub](https://huggingface.co/datasets/Alaamer/medium-articles-posts-with-content).

## Dataset Description

This dataset is a unique compilation that not only combines multiple sources but also ensures data quality through normalization and deduplication. A key feature is that all entries in the `text` column are unique - there are no duplicate articles in the final dataset.

### Data Sources:
#### Kaggle Sources:
- aiswaryaramachandran/medium-articles-with-content
- hsankesara/medium-articles
- meruvulikith/1300-towards-datascience-medium-articles-dataset

#### Hugging Face Sources:
- fabiochiu/medium-articles
- Falah/medium_articles_posts

## Features

- Combines multiple data sources into a single, unified dataset
- **Ensures uniqueness**: Each article appears only once in the dataset
- **Quality control**: 
  - Removes duplicate entries based on article text
  - Handles missing values
  - Normalizes data format
- Saves the final dataset in efficient Parquet format
- Publishes the dataset to Hugging Face Hub
