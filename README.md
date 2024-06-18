
# Wheel of Fortune Advanced Analysis

This repository contains an advanced analysis script for the "Wheel of Fortune" dataset using various Natural Language Processing (NLP) techniques and other high-end models.

## Dataset

The dataset captures a variety of categories from the "Wheel of Fortune" game show, including everyday topics like "Around The House" and whimsical challenges such as "Fictional Character" and "Movie Title."

## Analysis

The script performs the following analyses:

1. **Data Preprocessing**:
    - Converts text to lowercase
    - Removes punctuation
    - Tokenizes the text
    - Removes stopwords

2. **Exploratory Data Analysis (EDA)**:
    - Visualizes the distribution of categories

3. **Text Analysis**:
    - Generates a word cloud for the phrases

4. **Sentiment Analysis**:
    - Uses TextBlob and VADER to analyze the sentiment of the phrases

5. **Topic Modeling**:
    - Uses Latent Dirichlet Allocation (LDA) and Non-negative Matrix Factorization (NMF) to uncover hidden topics within the phrases

6. **Named Entity Recognition (NER)**:
    - Identifies entities within the phrases using spaCy

7. **Clustering**:
    - Uses TF-IDF vectorization and KMeans clustering to group similar phrases together

## Insights and Conclusions

### Insights

1. **Category Distribution**: The dataset includes various categories, with some categories appearing more frequently than others. This indicates that certain themes are more commonly used in the show.

2. **Word Cloud**: The word cloud visualization reveals the most common words used in the phrases, helping to understand the typical vocabulary and themes of the show.

3. **Sentiment Analysis**: The sentiment analysis shows that most phrases have a neutral sentiment, which aligns with the descriptive or factual nature of the phrases.

4. **Topic Modeling**: The topic modeling techniques provide insights into the different themes and commonalities among the phrases.

5. **Named Entity Recognition**: The NER analysis identifies various entities within the phrases, adding another layer of understanding to the context and content of the phrases.

6. **Clustering**: The clustering analysis groups similar phrases together, highlighting common patterns and themes across different categories.

### Conclusions

- The "Wheel of Fortune" dataset offers a rich and diverse collection of phrases spanning multiple categories and themes.
- Sentiment analysis reveals that the phrases are generally neutral, aligning with their engaging and family-friendly nature.
- Topic modeling and clustering techniques uncover underlying patterns and themes, useful for understanding the show's content and creating new phrases.
- NER adds depth to the understanding of the phrases by identifying specific entities, aiding in targeted and context-aware phrase creation.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/debjit-mandal/wheel-of-fortune-analysis.git
    cd wheel-of-fortune-analysis
    ```

2. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the script**:
    ```sh
    jupyter notebook advanced_analysis_wheel_of_fortune_advanced.ipynb
    ```

## Requirements

- pandas
- nltk
- matplotlib
- seaborn
- wordcloud
- textblob
- scikit-learn
- spacy
- vaderSentiment

Ensure you have the required spaCy model:
```sh
python -m spacy download en_core_web_sm
```

## License

This project is licensed under the MIT License.

## Acknowledgements

The dataset can be found in Kaggle: https://www.kaggle.com/datasets/darrylljk/wheel-of-fortune-answers

------------------------------------------------------------------------------------------------------

Feel free to suggest any kind of improvements.
