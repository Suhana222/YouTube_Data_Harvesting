### YouTube Data Harvesting and Warehousing using SQL and Streamlit

---

![streamlit](https://github.com/Suhana222/YouTube_Data_Harvesting/assets/167739067/12cffd6e-239f-403c-8154-e7eb40bd510d)

---

#### Overview:

The YouTube Data Harvesting and Warehousing Project is a Python-based tool designed to extract and analyze data from YouTube, including video metadata, comments, and channel information. This project provides a convenient way to gather valuable insights from YouTube content for various purposes such as research, analysis, and content curation.

#### Key Features:

1. **Video Metadata Extraction:** Retrieve detailed information about YouTube videos, including title, description, tags, view count, upload date, and more.

2. **Comment Retrieval:** Extract comments associated with specific videos or entire channels, enabling sentiment analysis and audience engagement insights.

3. **Channel Information Retrieval:** Obtain comprehensive information about YouTube channels, including subscriber count, total views, video count, and more.

4. **Flexible Data Export:** Export harvested data to various formats such as CSV, JSON, or directly into a database for further analysis and integration with other tools.

5. **Content Analysis:** Analyze trends, preferences, and engagement metrics for specific types of content or channels on YouTube.

6. **Audience Insights:** Understand audience demographics, behaviors, and preferences through comments and engagement metrics.

7. **Competitive Analysis:** Compare and benchmark your channel or content against competitors to identify strengths and areas for improvement.

8. **Research:** Conduct academic or market research leveraging YouTube data for insights into various topics, industries, or trends.

#### Technologies Used:

- **Python:** The programming language used for building the application and scripting tasks.
  
- **Streamlit:** A Python library used for creating interactive web applications and data visualizations.

- **YouTube API:** Google API is used to retrieve channel and video data from YouTube.

- **MongoDB:** The retrieved data is stored in a MongoDB database based on channel ID.

- **PostgreSQL:** A relational database used as a data warehouse for storing migrated YouTube data.

- **Pandas:** A data manipulation library used for data processing and analysis.

#### Installation and Setup:

1. **Install Python:** Install the Python programming language on your machine.

2. **Install Required Libraries:** Install the necessary Python libraries using pip or conda package manager. Required libraries include Streamlit, PostgreSQL, MongoDB, and Pandas.

3. **Set Up Google API:** Set up a Google API project and obtain the necessary API credentials for accessing the YouTube API.

4. **Configure Database:** Use MongoDB for storing the data and migrate it to PostgreSQL.

5. **Configure Application:** Update the configuration file or environment variables with the necessary API credentials and database connection details.

6. **Run the Application:** Launch the Streamlit application using the command-line interface.

#### Usage:

Once the project is set up and running, users can access the Streamlit application through a web browser. The application provides a user interface where users can perform the following actions:

1. Enter a YouTube channel ID to retrieve data for that channel.
   
2. Collect and store data for multiple YouTube channels.
   
3. Select a channel and migrate its data to the SQL data warehouse.
   
4. Search and retrieve data from the SQL database using various search options and creating queries.
   
5. Create a Streamlit application to visualize the data.

#### Conclusion:

The YouTube Data Harvesting and Warehousing project provides a powerful tool for retrieving, storing, and analyzing YouTube channel and video data. By leveraging PostgreSQL and Streamlit, users can easily access and manipulate YouTube data in a user-friendly interface. The project offers flexibility, scalability, and data visualization capabilities, empowering users to gain insights from the vast amount of YouTube data available.

---
