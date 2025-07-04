# 🎬 Netflix Movies & TV Shows Exploration

## 📌 Project Overview & Task Objective

This notebook explores the Netflix Movies and TV Shows dataset to uncover insights such as content distribution over time, type proportions (Movie vs TV Show), genre popularity, rating categories, content-producing countries, and content durations. The primary objective is to understand Netflix's content strategy using exploratory data analysis (EDA).

## 📂 Dataset Information

The project utilizes the `netflix_titles.csv` dataset, which contains information about movies and TV shows available on Netflix. Key features include `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genres), and `description`.

**Key Aspects:**
- Content distribution over time.
- Proportion of Movies vs. TV Shows.
- Popularity of different genres.
- Analysis of content ratings.
- Identification of top content-producing countries.
- Examination of content durations.

## ✨ Features

- Data loading and initial inspection.
- Handling missing values.
- Exploratory Data Analysis (EDA) to visualize content trends.
- Analysis of content types (movies vs. TV shows).
- Investigation of genre popularity and distribution.
- Examination of content ratings and their prevalence.
- Identification of key countries contributing to Netflix content.
- Analysis of content duration for both movies and TV shows.

## 🛠️ Installation

To run this notebook locally, you will need Python installed along with the following libraries. You can install them using pip:
```bash
pip install pandas numpy seaborn matplotlib
```

## 🚀 Approach

My approach to exploring the Netflix dataset involved the following steps:

- **Library Import**: Imported essential Python libraries for data manipulation (pandas, numpy), and visualization (matplotlib, seaborn).
  
- **Data Loading**: Loaded the `netflix_titles.csv` dataset into a pandas DataFrame.

- **Data Cleaning and Preparation**:
  - Handled missing values in relevant columns (e.g., `director`, `cast`, `country`).
  - Converted `date_added` to datetime objects for time-based analysis.
  - Extracted and processed genre information from the `listed_in` column.
    
- **Exploratory Data Analysis (EDA)**:
  - Analyzed the distribution of content types (Movie vs. TV Show).
  - Visualized content added over time to observe trends.
  - Explored the popularity of different genres using count plots.
  - Examined the distribution of content ratings.
  - Identified the top countries producing content for Netflix.
  - Analyzed the duration of movies and TV shows.

## 🧰 Technologies Used
- P Y T H O N
- P A N D A S
- N U M P Y
- M A T P L O T L I B
- S E A B O R N

## 📉 Visualizations


## 📊 Results and Insights

### Key Insights:
  - The analysis revealed trends in Netflix's content acquisition over the years, with a significant increase in recent times.
  - The proportion of movies versus TV shows was identified, showing the dominant content type.
  - Popular genres and content ratings were highlighted, providing insights into audience preferences.
  - Key contributing countries were identified, indicating global content sourcing.
  - Distribution of content durations provided insights into typical movie lengths and TV show season counts.
    
### Final Outcome:
  - This project successfully demonstrates a comprehensive EDA workflow for understanding a streaming content dataset.
  - The insights gained can inform content strategy and acquisition decisions for streaming platforms.

## 🧪 Usage

```bash
# 1. Clone the repository (assuming this notebook is part of a larger repository)
git clone <repository_url>

# 2. Navigate to the project directory
cd <project_directory>

# 3. Open the notebook
jupyter notebook Netflix_Movies_TV_Shows_Exploration.ipynb

```

## 🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## 📬 Contact

For questions or collaboration:
- GitHub: `AhsanNFt`
- Email: `syedahsan0991@gmail.com`

