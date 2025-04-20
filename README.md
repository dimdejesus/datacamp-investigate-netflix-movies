# Investigate Netflix Movie
Datacamp's first project in Associate Data Science Roadmap.

## Description
![alt text](./redpopcorn.jpg)

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry.

You work for a production company that specializes in nostalgic styles. You want to do some research on movies released in the 1990's. You'll delve into Netflix data and perform exploratory data analysis to better understand this awesome movie decade!

You have been supplied with the dataset `netflix_data.csv`, along with the following table detailing the column names and descriptions. Feel free to experiment further after submitting!

### The Data (**netflix_data.csv**)
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

## Questions and Answer
What I'll be placing in the answer are just text format please refer to [notebook.ipynb](./notebook.ipynb) for the code 

**Question #1**: What was the most frequent movie duration in the 1990s? Save an approximate answer as an integer called duration (use 1990 as the decade's start year).

**Answer**: The most frequest duration of movie in 90's is around **100 mins** based on the figure provided in [notebook.ipynb](./notebook.ipynb).

**Question #2**: A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s and save this integer as short_movie_count.

**Answer**: The number of short movies released in the 90's are **7** based on the figure provided in [notebook.ipynb](./notebook.ipynb).

## Analysis Steps
1. Data Loading: Used the given `netflix_data.csv` to analyze
2. Data Exploration: Look into the data and take advantage of what it gives
3. Data Processing: Use python, pandas, and numpy to filter the data to produce an answer to the question provided.
4. Visualization: Output the most frequest duration of the movie in 90's and count the short action movies.

## Libraries used
* Python
* Pandas
* Numpy

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgement
* **Datacamp's** Associate Data Science in Python
* **Datalab** - I only placed it here because I used only the free versioon which limits me to 3 workbooks only




