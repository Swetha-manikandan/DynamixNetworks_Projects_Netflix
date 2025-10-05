
## 🔍 Overview

The objective of this project is to analyze Netflix’s content catalog to identify:

- Content type distribution (Movies vs TV Shows)
- Yearly trends in content release
- Genre popularity
- Top countries producing Netflix content
- Ratings and duration insights

The interactive dashboard allows users to slice and filter data dynamically.

## 📦 Dataset

- **Source:** [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Size:** ~6,000+ records

### Dataset Features:

| Column | Description |
|--------|-------------|
| show_id | Unique ID for each show |
| type | Movie or TV Show |
| title | Title of the show |
| director | Director(s) |
| cast | Main cast |
| country | Country of production |
| date_added | Date it was added to Netflix |
| release_year | Original release year |
| rating | Age rating |
| duration | Duration (in minutes or seasons) |
| listed_in | Genre(s) |
| description | Short summary |

## ⚙️ Power BI Workflow

1. **Data Loading** – Import CSV into Power BI
2. **Data Cleaning** – Handle missing values, split genres, extract year/month, etc.
3. **Data Modeling** – Define relationships and calculated columns/measures
4. **Visualizations** – Create charts, cards, filters, and interactive slicers

## 📈 Key Insights

- Majority of content on Netflix is **Movies**
- Peak content additions were in **2019-2020**
- **United States** dominates content production
- Popular genres include **Dramas, Comedies, and Documentaries**
- Most movies are between **80–100 minutes** long

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel / Power Query (optional)**
- **Python (optional for preprocessing)**

## 🚀 Getting Started

To view or edit the dashboard:

1. Download the repository
2. Open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Load the data from `data/netflix_titles.csv` if prompted
4. Explore and interact with the dashboard

## ✅ Future Improvements

- Add time series forecasting on content release trends
- Integrate IMDb or Rotten Tomatoes ratings for richer analysis
- Deploy Power BI report to Power BI Service for public access

## 🤝 Contribution

Feel free to fork the repo, create new visuals, or add insights. Pull requests are welcome!

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Contact

For any questions or collaboration:

- GitHub: [Swetha-manikandan](https://github.com/Swetha-manikandan)
- LinkedIn: [Swetha Manikandan](https://linkedin.com/in/swetha-manikandanm)
