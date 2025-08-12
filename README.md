🎬 Movie Recommendation System
A content-based movie recommendation engine that suggests similar movies based on genres, keywords, taglines, cast, and director, using TF-IDF Vectorization and Cosine Similarity.

📌 Features
Recommends top 30 movies similar to a given movie.

Uses TF-IDF Vectorizer to convert text features into numerical vectors.

Calculates similarity using Cosine Similarity.

Works with the movies.csv dataset containing movie metadata.

🛠️ Technologies Used
Python

Pandas & NumPy

scikit-learn (TF-IDF & Cosine Similarity)

difflib (for fuzzy matching movie names)

Jupyter Notebook

📂 Dataset
The dataset movies.csv contains metadata such as:

Genres

Keywords

Tagline

Cast

Director

🚀 How It Works
Select relevant features for recommendations.

Fill missing values with empty strings.

Combine all selected features into a single string for each movie.

Convert combined text into numerical vectors using TF-IDF.

Compute cosine similarity scores between all movies.

Take a movie name as input and output the top 30 most similar movies.

📸 Example Output
markdown
Copy code
Enter your favourite movie name: Avatar  
Movies suggested for you:

1. Avatar  
2. Guardians of the Galaxy  
3. The Avengers  
4. Interstellar  
...  
📌 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/YourUsername/Movie-Recommendation-System.git
cd Movie-Recommendation-System
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open Jupyter Notebook and run:

bash
Copy code
jupyter notebook Movie_Recommendation_System.ipynb
📜 License
This project is licensed under the MIT License.
