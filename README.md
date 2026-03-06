🎬 Movie Recommendation System

An AI-powered Movie Recommendation System that suggests movies based on similarity between movie features.
This project demonstrates how Machine Learning and Data Processing can be used to build intelligent recommendation engines like those used by Netflix or Amazon.

       
📌 Features

     ✨ Smart Movie Recommendations

     Suggests similar movies based on the selected movie

    🎥 Movie Poster Fetching

    Automatically displays movie posters

    ⚡ Fast Recommendations

    Uses similarity matrix for quick predictions
    
    🧠 Machine Learning Based
    
    Content-based filtering using cosine similarity
    
    💻 Interactive UI
    
    Built with an easy-to-use interface

    

🛠️ Tech Stack


      Technology	Usage
      Python	Backend Logic
      Pandas	Data Processing
      Scikit-learn	Machine Learning
      Streamlit	Web Interface
      Pickle	Model Storage
      TMDB API	Movie Posters

      
📂 Project Structure



        movie-recommendation
        │
        ├── app.py                # Streamlit web app
        ├── movie_dict.pkl       # Movie data
        ├── similarity.pkl       # Similarity matrix
        ├── requirements.txt     # Dependencies
        ├── README.md            # Project documentation
        └── screenshots
            └── preview.png


            
⚙️ Installation

  Clone the repository from GitHub

    git clone https://github.com/Mukulkumarpandey/movie-recommendation.git

  Go to the project directory

    cd movie-recommendation

  Install dependencies

    pip install -r requirements.txt

Run the application

    streamlit run app.py

    
🎥 How It Works

    1️⃣ User selects a movie
    
    2️⃣ System finds similarity with other movies
    
    3️⃣ Top recommended movies are displayed
    
    4️⃣ Posters are fetched using TMDB API

🧠 Machine Learning Approach

    The system uses Content-Based Filtering.

Steps:

    Text preprocessing

    Feature extraction
    
    Cosine similarity calculation
    
    Recommendation generation
    
    This approach recommends movies with similar genres, keywords, and metadata.


          
🌟 Future Improvements

    User login system
    
    Deep learning recommendation model

