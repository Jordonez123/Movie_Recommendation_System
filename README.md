# Owner: Jordan Ordonez
## Project Name: Movie Recommendation System
### Friday, January 3, 2025

---

# **Movie Recommendation System**  

A Python project that helps users explore and discover movies based on genres, ratings, and recommendations. The project uses various data structures like dictionaries, lists, sets, and tuples to handle and process data efficiently.  

---

## **Features**
- **Search Movies by Genre**: Find movies that match your preferred genre.  
- **Rate Movies**: Submit ratings for movies and store them persistently.  
- **Top-Rated Movies**: View a list of the highest-rated movies.  
- **Recommendations**: Get personalized movie recommendations based on your preferences and rating history.  

---

## **Technologies Used**
- **Python**: Core programming language.  
- **JSON**: For storing and managing movie data and user ratings.  

---

## **Directory Structure**
```
movie-recommendation-system/
│
├── data/                  
│   ├── movies.json        # Movie database
│   ├── user_ratings.json  # User ratings storage
│
├── src/                   
│   ├── main.py            # Main application script
│   ├── utils.py           # Utility functions
│   ├── recommend.py       # Recommendation logic
│   ├── search.py          # Movie search logic
│   ├── ratings.py         # Handle user ratings
│
├── tests/                 
│   ├── test_recommend.py  # Tests for recommendation logic
│   ├── test_search.py     # Tests for search functionality
│   ├── test_ratings.py    # Tests for ratings functionality
│
├── docs/                  
│   ├── README.md          # Detailed project documentation
│
├── requirements.txt       # Python dependencies
├── .gitignore             # Ignored files for version control
├── README.md              # Overview of the project
```

---

## **Getting Started**

### Prerequisites
1. Install Python 3.8 or higher.  
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

---


### How to Run the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```  
2. Navigate to the `src` directory:  
   ```bash
   cd src
   ```  
3. Run the main script:  
   ```bash
   python main.py
   ```  

---

## **How It Works**
1. **Initial Data:**  
   - Movie data is stored in `movies.json`.  
   - User ratings are stored in `user_ratings.json`.  

2. **User Interaction:**  
   - Select options to search, rate, or get recommendations.  
   - Input your preferences, and the program fetches the relevant data.  

3. **Recommendations:**  
   - The system suggests movies based on your ratings and favorite genres.  

---

## **Future Enhancements**
- Integrate with an API like TMDb or IMDb for real-time movie data.  
- Add a web or GUI interface for better user experience.  
- Implement collaborative filtering for advanced recommendations.  

---

## **Contributing**
Contributions are welcome! Please open an issue or submit a pull request.  

---

## **License**
This project is open-source under the MIT License.  

---

