Movie Recommendation System:
A machine learning-based movie recommendation system that suggests similar movies based on genres, keywords, cast, and director. It utilizes TF-IDF Vectorization and Cosine Similarity for content-based filtering.


Project Overview:
 1. Analyzing movie metadata (genres, keywords, cast, director)
 2. Computing similarity scores using TF-IDF & Cosine Similarity
 3. Providing personalized recommendations
 4. Exposing an API for easy integration

Key Features:
 1. Content-based filtering using machine learning
 2. Real-time recommendations based on user input
 3. Customizable dataset – works with any movies.csv
 4. Scalable and lightweight solution

Methodology:
 1. Data Preprocessing
     Loaded movies.csv dataset
     Handled missing values in genres, keywords, tagline, cast, director
     Created combined text features for vectorization
2. Feature Extraction
     Applied TF-IDF Vectorization to extract text-based features
     Converted text into numerical feature vectors
3. Similarity Calculation
     Used Cosine Similarity to compute distances between movies
     Retrieved top-N similar movies for a given title
4. API Deployment
     Built a Flask API for real-time recommendations
     Allowed dynamic movie search via API

Technologies Used:
 1. Python -> Core programming language
 2. Pandas -> Data manipulation
 3. NumPy -> Numerical operations
 4. Scikit-Learn -> Machine learning & similarity calculation
 5. Flask -> API development
 6. Jupyter Notebook -> Model testing

Contact & Contribution
Found a bug? Want to contribute?
Feel free to open an issue or pull request in the repository.

📩 Email: vidhyay458@gmail.com
🔗 GitHub: https://github.com/yvidhya
