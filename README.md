# 🎬 Movie Recommendation System

## 📌 Overview
This **Movie Recommendation System** is built using **collaborative filtering**, where recommendations are generated based on movie ratings. It uses **correlation-based filtering** to find movies that are similar to user-preferred ones. The dataset includes user ratings and movie titles, which are analyzed to suggest highly-rated and frequently watched movies.

## 🚀 Features
- 📊 **User-Based Collaborative Filtering**: Suggests movies based on user preferences and ratings.
- 🎭 **Movie Similarity Analysis**: Uses **Pearson correlation** to find similar movies.
- 📈 **Data Visualization**: Displays rating distributions and relationships between popularity & ratings.
- 📂 **Movie Popularity Metrics**: Calculates average ratings and rating counts.

## 🛠 Technologies Used
- **Python**
- **Pandas & NumPy** (Data Handling)
- **Matplotlib & Seaborn** (Visualization)
- **Scikit-Learn** (Data Processing)
- **Collaborative Filtering** (Pearson correlation for recommendations)

## 📂 Installation & Setup
1. **Clone this repository**:
   ```sh
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   ```sh
   jupyter notebook Movie_Recommendation_System.ipynb
   ```

## 🎥 Usage
1. **Load the dataset**: The dataset contains movie ratings and titles.
2. **Analyze Ratings**:
   - Compute average ratings for each movie.
   - Count the number of ratings per movie.
3. **Generate Movie Recommendations**:
   - Select a movie title.
   - Compute similarity scores using correlation.
   - Display top movie recommendations.
4. **Visualize Insights**:
   - Plot rating distributions.
   - Analyze rating trends and density plots.

## 📜 Dataset
- **Movie Ratings Dataset** (`u.data` and `Movie_Id_Titles`)
- **Columns**:
  - `user_id`: Unique user identifier.
  - `item_id`: Movie ID.
  - `rating`: Movie rating (1-5 scale).
  - `timestamp`: Rating timestamp.
  - `title`: Movie name.

## 🔥 Future Enhancements
- 📢 Implementing **matrix factorization** techniques like SVD.
- 🏆 Expanding to **content-based filtering** using movie descriptions.
- 🚀 Deploying as a **web-based recommendation app**.

## 🤝 Contributing
Contributions are welcome! Feel free to **open an issue** or **submit a pull request**.

## 📜 License
This project is licensed under the **MIT License**.
