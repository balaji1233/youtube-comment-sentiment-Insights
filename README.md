# YouTube Sentiment Analysis 👍👎😊

This project introduces a dynamic web application that performs rigorous sentiment analysis on YouTube comments. Users can submit a YouTube link, and the application scrutinizes the sentiment of the associated comments. Additionally, it exhibits video details, channel specifics, and graphical representations of the sentiment analysis outcomes.
## Features ✨

 -Derives the video ID from a given YouTube link.
 -Harvests comments from the designated YouTube video and archives them in a CSV file. 💬📑
 -Executes sentiment analysis on the comments utilizing the VADER (Valence Aware Dictionary and sEntiment 
  Reasoner) sentiment analysis instrument. 😃😠😐
 -Fabricates bar charts and scatter plots to illustrate the sentiment analysis findings. 📊📈
 -Procures video and channel specifics from the YouTube API. 📺🔍
-Offers an interactive web interface via Streamlit. 🌐✨

## Installation 🛠️

1. Clone the repository:

2. Install the required dependencies:

3. Obtain a YouTube Data API key from the [Google Cloud Console](https://console.cloud.google.com/) and replace `YOUR_API_KEY` in `YoutubeCommentScrapper.py` with your actual API key.

4. Run the application:


## Usage 🚀

1. Open the application in your web browser.

2. Enter a valid YouTube link in the sidebar. 🔗

3. Wait for the application to retrieve the video and channel information, save the comments to a CSV file, perform sentiment analysis, and display the results. ⌛

4. Explore the sentiment analysis results, video information, and channel information. 📈📺







