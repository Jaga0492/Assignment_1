#  Youtube - DS_YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit ( Assignment_1 )
 
YouTube Data Harvesting and Warehousing is an innovative project aimed at empowering users to seamlessly access and analyze data from a multitude of YouTube channels. Employing a sophisticated technological stack, the application utilizes SQL, MongoDB, and Streamlit to deliver a user-friendly interface, enabling users to effortlessly retrieve, save, and query YouTube channel and video data.

# Tools and Libraries Utilized:

# Streamlit:
Streamlit, a powerful Python library, is employed to craft an intuitive and user-friendly UI. This interface facilitates seamless interaction, empowering users to conduct data retrieval and analysis operations with ease.

# Python:
Renowned for its versatility and readability, Python serves as the primary programming language for the comprehensive development of the application. From data retrieval and processing to analysis and visualization, Python underpins the entire project.

# Google API Client:
The project leverages the googleapiclient library to establish communication with various Google APIs, notably YouTube's Data API v3. This integration facilitates the extraction of crucial information such as channel details, video specifics, and comments, providing developers with efficient access to YouTube's extensive data resources.

# MongoDB Atlas:
MongoDB Atlas, a robust cloud-based database service tailored for MongoDB, is utilized to store data acquired from YouTube's Data API v3. This integration ensures a fully managed, scalable, and hassle-free database solution, promoting efficient data management practices.

# PostgreSQL:
As an open-source, advanced, and highly scalable database management system, PostgreSQL is integrated into the project. Renowned for its reliability and extensive features, PostgreSQL provides a robust platform for storing and managing structured data, supporting various data types and advanced SQL capabilities.

# Ethical Considerations in YouTube Data Scraping:
Engaging in the scraping of YouTube content necessitates a principled and responsible approach. Adherence to YouTube's terms and conditions, obtaining appropriate authorization, and compliance with data protection regulations are foundational principles. Responsible handling of collected data is paramount, ensuring privacy, confidentiality, and guarding against misuse or misrepresentation. Additionally, the project acknowledges the potential impact on the platform and its community, striving for a fair and sustainable scraping process that upholds integrity.

# Required Libraries:

googleapiclient.discovery
streamlit
psycopg2
pymongo
pandas
# Features:
  The YouTube Data Harvesting and Warehousing application boasts the following functionalities:

Retrieval of channel and video data from YouTube using the YouTube API.
Storage of data in a MongoDB database, functioning as a comprehensive data lake.
Migration of data from the data lake to a SQL database, optimizing for efficient querying and analysis.
Search and retrieval of data from the SQL database, supported by diverse search options.
