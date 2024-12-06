Hybrid Book Recommendation System

A comprehensive hybrid book recommendation system combining collaborative filtering and content-based filtering to provide personalized book suggestions based on user preferences and demographic data.

Features

	•	Hybrid Approach: Combines Collaborative Filtering (CF) using Spark ALS and Content-Based Filtering (CBF) for accurate recommendations.
	•	User Demographics: Utilizes user age, location (city, country), preferred book categories, and languages for content-based filtering.
	•	Book Metadata: Integrates book details like title, author, publisher, and categories for improved recommendations.
	•	Scalable Architecture: Designed to handle large datasets efficiently using distributed processing with Spark.

How It Works

	1.	Collaborative Filtering (CF)
	•	Uses Apache Spark’s ALS (Alternating Least Squares) model to predict user-book interaction based on existing ratings.
	•	Finds similar users to suggest books they enjoyed.
	2.	Content-Based Filtering (CBF)
	•	Leverages user demographic data and book metadata to suggest books matching individual preferences.
	•	Uses techniques like TF-IDF vectorization and cosine similarity to identify relevant books.
	3.	Hybrid Model
	•	Combines the scores from CF and CBF to produce the final recommendation list.
	•	Ensures diverse and personalized suggestions for each user.

Technologies Used

	•	Programming Languages: Python
	•	Libraries and Frameworks:
	•	Pandas, NumPy, Scikit-learn (for preprocessing and modeling)
	•	PySpark (for collaborative filtering)
	•	Matplotlib, Seaborn (for visualizations)
	•	Tools: Jupyter Notebook
	•	Platform: Google Cloud Vertex AI (optional for large-scale datasets)

Usage

	•	Provide user input (age, city, country, preferred category, language, etc.) in the interface.
	•	The system outputs a ranked list of book recommendations.

Results

	•	Evaluation metrics like RMSE and precision-recall demonstrate the effectiveness of the hybrid approach.
	
Future Enhancements

	•	Add a front-end interface for user interaction.
	•	Optimize performance for real-time recommendations.
	•	Incorporate additional features like reviews and book cover analysis.

Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your proposed changes.

Acknowledgments

created by azadhalhalli
