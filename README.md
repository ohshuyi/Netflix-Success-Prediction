# Netflix Success Prediction
This project investigates the factors contributing to content success on Netflix. By predicting the attributes of successful content, we aim to provide insights that could guide Netflix in producing content that resonates with its audience. Unlike recommendation systems that focus on personalization, this project focuses on analyzing content success from a production and marketing perspective.

# 📁 Folder Structure
```
├── data                                   # data folder containing csv files
│   ├── combined_data.csv                  # combined dataset of top 200 and bottom 200 reviews
│   ├── data.csv                           # kaggle dataset 1
│   ├── imdb_bottom_200_reviews.csv        # crawled dataset for bottom 200 reviews
│   ├── imdb_top_200_reviews.csv           # crawled dataset for top 200 reviews
│   ├── merged_bottom_200_reviews.csv      # merged dataset of bottom 200 reviews and original dataset
│   ├── merged_data.csv                    # merged dataset of kaggle dataset 1 & 2
│   ├── merged_top_200_reviews.csv         # merged dataset of top 200 reviews and original dataset
│   ├── netflix_data_preprocessed.csv      # final dataset with data preprocessed
│   ├── netflix_movies.csv                 # kaggle dataset 2
│   ├── review_analysis_results.csv        # PCA & K-Means clustering analysis dataset for reviews
│   └── updated_combined_data.csv          # final dataset with missing values filled in
│
├── LeeEun_OhShuYi_DataMining_TEAM9.ipynb  # Notebook for Data Mining Project
└── README.md
```

# Dataset Details
Datasets were obtained from Kaggle:
* [Dataset 1](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset) - ```data.csv```
* [Dataset 2](https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset) - ```netlix_movies.csv```

Based on the imdbAverageRating from the combined dataset, reviews were crawled for the top 200 and bottom 200 pieces of content.

