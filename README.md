# News Analysis

This project downloads news articles using the `newsapi.org` API, cleans the news data, applies LDA for topic modeling, and creates interactive word clouds. Clicking on a word in the word cloud displays related news articles for that word.

## Features
- Download news articles by topic using the `newsapi.org` API
- Clean and preprocess the news data
- Apply LDA for topic modeling
- Generate word clouds based on topic terms
- Interactive word clouds displaying related news articles on click

## Requirements
- Python 3.6+
- requests
- pandas
- nltk
- wordcloud
- matplotlib
- bash

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/news-tweets-analysis.git
    cd news-tweets-analysis
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up your API keys:
    - Create a `.env` file in the root directory with your API keys:
        ```
        NEWS_API_KEY=your_newsapi_key
        ```

## Usage
1. Download news articles:
    ```bash
    python download_news.py
    ```

2. Clean and preprocess the news data:
    ```bash
    python clean_news.py
    ```

3. Apply LDA for topic modeling:
    ```bash
    python lda_topic_modeling.py
    ```

4. Generate and serve the word cloud:
    ```bash
    python generate_wordcloud.py
    ```

5. Open your browser and navigate to `http://localhost:5000` to interact with the word cloud.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
