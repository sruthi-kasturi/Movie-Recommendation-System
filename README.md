# 🎬 Movie Recommendation System  

## 📌 Overview  
This **Movie Recommendation System** is built using **collaborative filtering**, where recommendations are generated based on movie ratings. It uses **correlation-based filtering** to find movies that are similar to user-preferred ones. The dataset includes user ratings and movie titles, which are analyzed to suggest highly-rated and frequently watched movies.  

This project was completed as part of the **Pierian Training** course on **Machine Learning & Data Science**.  

## 📂 Dataset  
The dataset used is the **MovieLens dataset**, sourced from [GroupLens](https://grouplens.org/datasets/movielens/). It consists of:  
- **User ratings** of movies  
- **Movie metadata** (titles and IDs)  

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

## 🔥 Future Enhancements  
- 📢 Implementing **matrix factorization** techniques like SVD.  
- 🏆 Expanding to **content-based filtering** using movie descriptions.  
- 🚀 Deploying as a **web-based recommendation app**.  

## 🏆 Credits  
This project was completed as part of the **Pierian Training** course on **Machine Learning & Data Science**. The dataset is provided by **[GroupLens](https://grouplens.org/datasets/movielens/)**.  

## 🤝 Contributing  
Contributions are welcome! Feel free to **open an issue** or **submit a pull request**.  

## 📜 License  
This project is licensed under the **MIT License**.  
