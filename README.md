# Youtube_Data_Harvesting
![Uploading image.png…]()



The code imports multiple libraries at the beginning, including libraries for YouTube API, file handling, MongoDB, SQL, pandas, numpy, dashboard, and encryption.
The code uses the Streamlit library to configure the GUI layout and display a title for the dashboard.
The code defines a data collection zone where the user can enter a YouTube channel ID and click a button to retrieve data from the YouTube API and store it in a MongoDB database.
The code retrieves channel data, video IDs from the channel's playlist, and video data using the YouTube API. It also processes the retrieved data and stores it in a dictionary format.
The code establishes a connection to MongoDB, creates a database and collection, inserts or updates the collected data in the collection, and prints the result of the insertion operation. It then closes the MongoDB connection.
