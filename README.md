# Movie Recommendation System using TF-IDF & Cosine Similarity

##  Overview
This project implements a content-based Movie Recommendation System using Natural Language Processing techniques. The system recommends movies based on genre similarity using vectorization and cosine similarity.

##  Objective
To build a recommendation engine that suggests movies similar to a given movie by analyzing genre-based textual features.

##  Methodology

The system follows these steps:

1. Data preprocessing and cleaning  
2. Genre feature extraction  
3. Text vectorization using:
   - CountVectorizer
   - TF-IDF (Term Frequency – Inverse Document Frequency)
4. Cosine similarity computation  
5. Recommendation function to retrieve top-N similar movies  

##  Dataset
The dataset contains movie titles and genre information used to compute similarity between movies.

##  Machine Learning Concepts Used
- Feature Engineering
- Text Vectorization
- TF-IDF Transformation
- Similarity Metrics (Cosine Similarity)

##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

##  How It Works
- Genres are converted into numerical vectors.
- Cosine similarity calculates similarity scores between movies.
- The system returns the top similar movies based on similarity ranking.

##  Future Improvements
- Include cast, director, and keywords for richer feature representation
- Implement collaborative filtering
- Build a hybrid recommendation system
- Deploy using Streamlit or Flask
- Evaluate performance using ranking metrics (Precision@K, Recall@K)

##  Author
Syed Junaid Ali Shah  
MS Computer Science (Cybersecurity)  
Machine Learning for AI-Driven Security
