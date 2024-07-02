# PRODIGY_DS_04
## Project Description
This project aims to perform sentiment analysis on Twitter data using a dataset of tweets. The analysis involves data cleaning, sentiment distribution visualization, and brand-specific sentiment analysis, particularly focusing on tweets related to Microsoft.

1.Table of Contents
2.Installation
3.Usage
4.Project Structure
5.Data Description
6.Analysis Steps
7.Visualization
8.Contributing
9.License

## Data Description
The dataset twitter_training.csv contains tweets with the following columns:

ID: Unique identifier for each tweet.
Entity: The entity (e.g., brand) mentioned in the tweet.
Sentiment: The sentiment associated with the tweet (Positive, Negative, Neutral).
Content: The text content of the tweet.
## Analysis Steps
Data Loading: Load the dataset into a pandas DataFrame.
Data Cleaning: Handle missing values and remove duplicates.
Sentiment Distribution: Calculate and visualize the distribution of sentiments in the dataset.
Brand-Specific Analysis: Filter tweets related to Microsoft and analyze their sentiment distribution.
Text Analysis: Perform text analysis using TextBlob for additional insights.
## Visualization
The project includes visualizations using Plotly for better insights into the sentiment distribution:

Bar Chart: Displays the overall sentiment distribution across all tweets.
Pie Chart: Shows the sentiment distribution specifically for tweets mentioning Microsoft.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
