# Guvi-project-1
youtube data harvesting and warehousing

YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a GoogleColab database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.


Retrieving data from the YouTube API
Storing data in GoogleColab
Migrating data to a SQL data warehouse

Retrieve data from the YouTube API, including channel information, playlists, videos, and comments.
Store the retrieved data in a GoogleColab database.
Migrate the data to a SQL data warehouse.
Analyze and visualize data using Streamlit and Plotly.
Perform queries on the SQL data warehouse.
Gain insights into channel performance, video metrics, and more.

The project utilizes the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments. By interacting with the Google API, we collect the data and merge it into a SQL file.

The application allows users to migrate data from GoogleColab to a SQL data warehouse. Users can choose which channel's data to migrate. To ensure compatibility with a structured format. The information is segregated into separate tables, including channels, playlists, videos, and comments, utilizing SQL queries.

Channel analysis includes insights on playlists, videos, subscribers, views, likes, comments, and durations. Gain a deep understanding of the channel's performance and audience engagement through detailed visualizations and summaries.
Video analysis focuses on views, likes, comments, and durations, enabling both an overall channel and specific channel perspectives. Leverage visual representations and metrics to extract valuable insights from individual videos.

The Streamlit app provides an intuitive interface to interact with the charts and explore the data visually. Users can customize the visualizations, filter data, and zoom in or out to focus on specific aspects of the analysis.



