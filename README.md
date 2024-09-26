# WhatsApp Chat Analyzer

A data analysis project that allows users to analyze WhatsApp chat data. Using Streamlit for the frontend, the app provides various insights into WhatsApp chats, including message frequency, busiest users, most common words, emojis, and activity heatmaps. This project uses Python for the backend and supports machine learning and NLP techniques for text analysis.

## Features

- *Preprocessing*: Cleans and structures the WhatsApp chat data, separating user names, messages, and timestamps.
- *Statistical Insights*: Provides total message count, word count, media shared, and links shared in the chat.
- *Activity Analysis*: Analyzes user activity by month, day, and week, along with visualizing the busiest hours.
- *Most Active Users*: Identifies the most active users in group chats.
- *Word Cloud*: Generates a word cloud based on the most frequent words used in the chat.
- *Emoji Analysis*: Analyzes the frequency of emojis used by participants.
- *Visualizations*: Provides different types of plots like timelines, bar charts, and heatmaps.

## Tech Stack

- *Frontend*: [Streamlit](https://streamlit.io/)
- *Backend*: Python
- *Data Visualization*: Matplotlib, Seaborn, WordCloud
- *Data Processing*: Pandas, URLExtract, Regex, Emoji
- *Version Control*: Git, GitHub

## Installation

1. Clone the repository:

    bash
    git clone https://github.com/Abhilashkale/whatsappchatanalyzer.git
    

2. Navigate to the project directory:

    bash
    cd whatsappchatanalyzer
    

3. Install the required dependencies:

    bash
    pip install -r requirements.txt
    

## Usage

1. To run the app locally, use the following command:

    bash
    streamlit run app.py
    

2. Upload a WhatsApp chat .txt file when prompted.

3. View various statistics and visualizations based on the analysis of the chat data.

## Project Structure

- app.py: Main file to run the Streamlit app.
- preprocessor.py: Contains the preprocessing logic for cleaning and structuring WhatsApp chat data.
- helper.py: Includes various helper functions for generating statistics, word clouds, and activity maps.
- requirements.txt: Lists all the required Python libraries.

## Screenshots

### Home Page
![Home](path/to/screenshot.png)

### Example of Chat Analysis
![Analysis](path/to/screenshot2.png)

## Dependencies

- streamlit
- matplotlib
- seaborn
- urlextract
- wordcloud
- pandas
- emoji

Install the dependencies using pip install -r requirements.txt.

## Contributing

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.

## License

This project is licensed under the MIT License.

---

Developed by [Abhilash Kailas Kale](mailto:abhilashkale238@gmail.com).
