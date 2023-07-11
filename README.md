# Anime Recommendation

To view the user's portfolio blog on the anime recommendation system using collaborative filtering, please visit [My Blog](https://danielrs.systeme.io/anime-recommendation-system-using-collaborative-filtering) to see the explanation of the notebook.



Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

# Anime Recommendation Dataset

This repository contains two datasets related to anime shows and user ratings:

## anime-filtered.csv

Based on 2021 data, this dataset contains information about various anime shows. Here's a brief overview of the dataset:

### Columns

The dataset includes columns like `anime_id`, `Name`, `Score`, `English name`, `Japanese name`, `synopsis`, `Type`, `Episodes`, `Aired`, `Premiered`, `Producers`, `Licensors`, `Studios`, `Source`, `Duration`, `Rating`, `Ranked`, `Popularity`, `Members`, `Favorites`, `Watching`, `Completed`, `On-Hold`, and `Dropped`.

### Anime Details

Each row represents a different anime show, identified by a unique `anime_id`. The `Name` column provides the title of the anime show, both in English and Japanese. The `Score` column indicates the average rating score of the anime show. The `synopsis` column gives a brief summary of the storyline or plot of each anime. The `Type` column categorizes the anime as a TV series, movie, or other format. The `Episodes` column specifies the total number of episodes for each anime show.

### Airing Information

The `Aired` column shows the date range when the anime aired. The `Premiered` column indicates the specific season and year of the anime's premiere.

### Production Details

The `Producers`, `Licensors`, and `Studios` columns list the companies involved in producing and distributing the anime. The `Source` column indicates the medium from which the anime was adapted, such as manga or original.

### Duration and Rating

The `Duration` column specifies the length of each episode. The `Rating` column provides the target audience rating for the anime.

### Popularity and User Engagement

The `Ranked` column ranks the anime based on popularity or user ratings. The `Popularity` column represents the popularity rank of the anime. The `Members` column indicates the number of members who have the anime in their list. The `Favorites` column shows the number of users who have marked the anime as their favorite.

### User Engagement Metrics

The `Watching`, `Completed`, `On-Hold`, and `Dropped` columns represent the number of users in each respective category, indicating the level of user engagement with the anime.

This dataset provides valuable information for analyzing and understanding the characteristics, ratings, popularity, and viewership of different anime shows.

## user-filtered.csv

This dataset contains information about user ratings for different anime shows. Here's a brief overview of the dataset:

### Columns

The dataset includes columns like `user_id`, `anime_id`, and `rating`.

### User and Anime Identification

Each row represents a user's rating for a specific anime show. The `user_id` column identifies the user, while the `anime_id` column identifies the corresponding anime.

### Rating

The `rating` column represents the user's rating for the anime on a scale from 0 to 10, with 10 being the highest rating.

This dataset provides valuable information for analyzing and understanding user preferences and ratings for various anime shows.

## Acknowledgments

I would like to express my gratitude to the following sources for their contributions to this dataset:

- Kaggle: Anime Recommendation Database, MyAnimeList Dataset - This dataset served as the basis for my analysis and recommendation system project. I would like to thank the contributors who originally collected and shared this dataset, as it provided valuable insights and data for my research.
- MyAnimeList - I am grateful to the platform for hosting the original data and providing a comprehensive database of anime titles and user ratings. Their platform has been an invaluable resource for anime enthusiasts and researchers alike.
## Dataset Source

The dataset was obtained from [MyAnimeList](https://myanimelist.net/), a popular anime and manga database. You can get the data from [Anime Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset), which provides access to the database's anime and manga information.

## License

This dataset is licensed under the [Open Database License](https://opendatacommons.org/licenses/odbl/1.0/). You are free to use, share, and modify this dataset for any purpose, as long as you attribute the original source and follow the terms of the license.


This project is a simple anime recommendation system that suggests anime based on user preferences.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
