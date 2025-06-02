# 🎵 Spotify Song Classification with Random Forest

This project utilizes a Random Forest classifier to predict song popularity based on audio features from Spotify's dataset. The goal is to distinguish between popular and less popular tracks using machine learning techniques.

## 📊 Notebook

👉 [View the Kaggle Notebook](https://www.kaggle.com/code/philbertchan/spotify-song-classification-with-random-forest)

## 🔍 Key Insights

- **Model Performance**: The Random Forest classifier achieved an accuracy of approximately 85% in distinguishing popular songs.
- **Feature Importance**: Audio features like danceability, energy, and loudness were significant predictors of a song's popularity.
- **Data Imbalance**: Addressed class imbalance using resampling techniques to ensure model robustness.

## 🧰 Tools Used

- **Python**: Data manipulation and model building
- **Pandas & NumPy**: Data preprocessing
- **Scikit-learn**: Implementing the Random Forest classifier
- **Matplotlib & Seaborn**: Data visualization
- **Kaggle**: Notebook environment and dataset

## 📁 Project Structure
<pre>
  spotify-song-classification/
├── data/
│ └── spotify_dataset.csv
├── notebooks/
│ └── spotify_classification.ipynb
├── visuals/
│ └── feature_importance.png
├── README.md
└── .gitignore
</pre>

## 🚀 Future Improvements
- Explore other classification algorithms like XGBoost or SVM for performance comparison.
- Incorporate additional features such as lyrical content or release date.
- Deploy the model as a web application using Streamlit for interactive predictions.


