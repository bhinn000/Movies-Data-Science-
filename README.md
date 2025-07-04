![Python Version](https://img.shields.io/badge/python-3.11-blue.svg)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_NOTEBOOK_URL)


**Movie Dataset Analysis**
This project explores a dataset of movies with columns like release date, title, popularity, vote counts, genre, and more. The main goals were to clean and preprocess the data and create some visualizations.

**Data Preprocessing**
    Converted Release_Date from object to date format and kept only the release year.
    Removed unnecessary columns: Overview, Original_Language, and Poster_Url.
    Categorized the Vote_Average column into four labels: Not_Popular, Below_Avg, Average, Popular.
    Split the Genre column by comma to separate multiple genres per movie and exploded it.
    Checked for duplicates and missing values.

**Data Visualization**
    Used Seaborn and Matplotlib to create plots:
    
    Genre Count: Visualized how many movies were in each genre.
    Vote Average: Visualized the distribution of vote categories.
    Most Popular Movie: Found that "Spider-Man: No Way Home" is the most popular movie across genres like Action, Adventure, and Science Fiction.
    Least Popular Movie: Found the least popular movies, like "The United States vs. Billie Holiday" and "Threads," with various genres.
    Most Movies Released by Year: Found that 2020 had the highest number of movies released.

**Technologies Used**
    Python
    Pandas
    Seaborn 
    Matplotlib
    
**  How to Run**
    Clone this repo.
    Open Movies Related DS.ipynb in Google Colab or Jupyter.
    Run the notebook cells to see the analysis.

** 📌 Conclusion**
    This project gave me hands-on practice in data cleaning and visualization. It’s also a great example to show recruiters how I handle messy data and turn it into insights!
