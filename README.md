# 🎬 Netflix Data Analysis

This project analyzes Netflix movie data using Python to uncover trends, viewer preferences, and genre popularity. Through data cleaning, transformation, and visualization, we answer critical business questions and deliver insights from Netflix’s movie catalog.

---

## 📊 Key Questions Explored

- What is the most frequent genre of movies released on Netflix?
- Which genre has the highest vote count?
- What movie got the highest popularity? What’s its genre?
- What movie got the lowest popularity? What’s its genre?
- Which year had the most number of movies filmed?

---

## 🛠️ Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

---

## 🔍 Analysis Highlights

The project followed a structured data analysis pipeline to ensure data quality and clear insights:

- Explored dataset statistics to understand structure and distribution
- Checked for duplicate entries and removed them
- Cleaned and preprocessed data:
  - Changed data types of appropriate columns
  - Dropped unnecessary or irrelevant columns
  - Removed null values to ensure accuracy
- Categorized and labeled key features for clarity
- Processed the `genre` column:
  - Split comma-separated genres into lists
  - Used `explode()` to normalize data with one genre per row per movie
- Created visualizations to address business questions:
  - Used bar charts, histograms, and tabular views
  - Each of the 5 questions was answered with both summary statistics and visual interpretation

---

## 📌 Key Insights

- 🎭 **Most Frequent Genre:**  
  Drama is the most frequent genre in the dataset, appearing in over **14%** of entries among 19 genres.

- 🗳️ **Genre with Highest Votes:**  
  Drama again tops popularity, representing more than **18.5%** of the most voted movies (out of 6520 high-vote entries).

- 🌟 **Highest Popularity Movie:**  
  **Spider-Man: No Way Home** has the highest popularity score and belongs to the genres: **Action**, **Adventure**, and **Science Fiction**.

- 🕳️ **Lowest Popularity Movie:**  
  **The United States, Thread** has the lowest popularity score, and it falls under genres: **Music**, **Drama**, **War**, **Sci-Fi**, and **History**.

- 🎞️ **Most Filmed Year:**  
  The year **2020** had the highest number of movies released on Netflix.


