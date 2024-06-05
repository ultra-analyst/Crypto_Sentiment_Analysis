### Cryptocurrency Sentiment Analysis Project

#### Project Overview
In this project, we analyzed the sentiment of news articles related to Solana, Cardano, and Chainlink to understand their relationship with cryptocurrency price movements. By using natural language processing (NLP) techniques and financial data, we aimed to provide insights into how market sentiment influences or correlates with cryptocurrency prices.

#### Data Collection
We collected news articles from Google News using RSS feeds for Solana, Cardano, and Chainlink. The CoinGecko API was used to gather historical price data for these cryptocurrencies over the same period.

#### Data Cleaning and Preprocessing
The text data from news articles was cleaned to remove HTML tags, URLs, and non-alphabetic characters. The cleaned text was then tokenized, and common stop words were removed to focus on meaningful words.

#### Sentiment Analysis
We used the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool to classify the sentiment of the news articles. Each article was scored for positive, negative, neutral, and compound sentiment.

#### Data Alignment and Correlation Analysis
We aligned the sentiment data with corresponding dates of the historical price data. Average daily sentiment scores were computed and matched with daily price data to perform a correlation analysis.

#### Visualization
We created line plots to visualize sentiment scores and price movements over time for each cryptocurrency. These visualizations helped us observe how sentiment and price fluctuated together.

#### Key Findings
- Sentiment analysis revealed varying levels of positive, neutral, and negative sentiment for each cryptocurrency.
- Correlation analysis showed notable relationships between sentiment scores and price movements, varying in strength and direction.
- Visualizations provided a comprehensive understanding of how public sentiment can influence or predict market behavior in the cryptocurrency space.

#### Conclusion
This project demonstrated the potential of sentiment analysis as a tool for understanding and predicting cryptocurrency market trends. Combining NLP techniques with financial data analysis offered valuable insights into the dynamics between public sentiment and cryptocurrency prices.

### Technologies Used
- **Programming Languages**: Python
- **Libraries**: NLTK, VADER, Pandas, Matplotlib, BeautifulSoup, Requests, Pycoingecko
- **APIs**: Google News RSS, CoinGecko API
