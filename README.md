
# 🎧 Audio Features & Song Popularity Analysis

## 📌 Project Overview

An Exploratory Data Analysis (EDA) project that explores music characteristics and investigates patterns associated with song popularity using Python.

The project analyzes different audio features, genres, artists, release years, and popularity scores to discover useful patterns in music data.

## 🎯 Project Objectives

- Explore the distribution of song popularity.
- Analyze audio features such as energy, danceability, valence, and acousticness.
- Compare average popularity across music genres.
- Investigate relationships between audio features and popularity.
- Identify popular songs and compare artist-level performance.
- Detect missing values, duplicate records, and potential outliers.
- Generate meaningful observations and business insights.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

```text
Audio-Song-Popularity-EDA/
│
├── data/
│   └── audio_features.csv
│
├── notebooks/
│   └── audio_popularity_eda.ipynb
│
└── README.md
```

## 📊 Dataset Description

The dataset contains 500 unique song records after duplicate removal, with information about artists, genres, release years, audio characteristics, and popularity.

### Key Features

- `Track_Name` – Name of the song
- `Artist` – Artist associated with the song
- `Genre` – Music genre
- `Release_Year` – Year of release
- `Duration_Min` – Song duration in minutes
- `Danceability` – Measure of how suitable a track is for dancing
- `Energy` – Measure of musical intensity
- `Valence` – Measure associated with the musical positivity of a track
- `Acousticness` – Measure of acoustic characteristics
- `Instrumentalness` – Likelihood that a track contains no vocals
- `Speechiness` – Measure of spoken-word characteristics
- `Tempo_BPM` – Tempo in beats per minute
- `Loudness_dB` – Overall loudness
- `Popularity` – Song popularity score

## 🔍 Analysis Performed

### 1. Data Understanding
- Dataset shape and column inspection
- Data types and summary statistics
- Numerical and categorical feature analysis

### 2. Data Cleaning
- Identified and removed duplicate records
- Checked missing values
- Filled missing categorical values
- Imputed missing numerical values using the median

### 3. Exploratory Data Analysis
- Genre distribution
- Song popularity distribution
- Audio feature distributions
- Top 10 most popular songs
- Average popularity by genre
- Artist-level popularity comparison
- Popularity trends across release years

### 4. Relationship Analysis
- Energy vs. Popularity
- Danceability vs. Popularity
- Valence vs. Popularity
- Genre vs. Energy
- Correlation heatmap

### 5. Advanced Analysis
- Outlier detection using the IQR method
- Popularity categorization into Low, Medium, and High
- Comparison of audio characteristics across popularity groups
- Analysis of genres represented among highly popular songs

## 📈 Visualizations

The notebook includes:
- Histograms
- Boxplots
- Bar charts
- Scatter plots with trend lines
- Line charts
- Correlation heatmaps

## 💡 Key Insights

The analysis explores:

- How average popularity differs across music genres.
- Whether energy, danceability, and valence are associated with popularity.
- How audio characteristics vary among popularity groups.
- Which artists and songs rank highly in the dataset.
- How popularity patterns vary across release years.
- Which observations may require further investigation.

The findings describe patterns in this dataset and do not establish that any audio feature causes a song to become popular.

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/sanigasudheer/Audio-Song-Popularity-EDA.git
```

### Step 2: Open the project folder

```bash
cd Audio-Song-Popularity-EDA
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/audio_popularity_eda.ipynb` and run the cells in order.

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Statistical Summaries
- Correlation Analysis
- Outlier Detection
- Feature Engineering
- Analytical Thinking
- Insight Generation

## 👩‍💻 Author

**Saniga Sudheer**

Aspiring Data Analyst

