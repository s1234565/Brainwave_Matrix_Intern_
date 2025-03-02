Facebook Sentiment Analysis
This project analyzes Facebook post texts to determine public sentiment and visualize trends over time. Using VADER sentiment analysis, posts are categorized as Positive, Neutral, or Negative. Various visualizations, including sentiment trends, distribution, and engagement metrics (likes, comments), help explore the data.

Steps:
Importing Libraries and Loading Data
Libraries like pandas, matplotlib, nltk, seaborn are used for data processing and visualization. Facebook data is loaded using pd.read_csv().

Data Preprocessing
Special characters are removed, text is converted to lowercase, and missing values are handled by filling in default values or using the mean.

Sentiment Analysis
VADER sentiment analysis assigns a sentiment score to each post, classifying them into Positive, Neutral, or Negative categories.

Time Analysis
Sentiment scores are averaged over time, and trends are visualized using a line plot.

Visualizations

Pie Chart: Sentiment distribution
Histogram: Sentiment score distribution
Boxplot: Sentiment score by category
Word Cloud: Common words per sentiment
Bar Chart: Count of posts per sentiment
Heatmap: Correlation between likes, comments, and sentiment
Boxplot: Likes/comments distribution by sentiment
Insights:
Trends: Tracks sentiment shifts over time.
Engagement: Analyzes likes, comments, and sentiment relationships.
Word Clouds: Highlights frequently used words in different sentiment categories.
