# Anime Recommendation

To view the user's portfolio blog on the anime recommendation system using collaborative filtering, please visit [My Blog](https://danielrs.systeme.io/anime-recommendation-system-using-collaborative-filtering) to see the explanation of the notebook.



Due to the use of `plotly.express` and `plotly.graph_objects`, the visualizations in this code cannot be displayed on GitHub. To view the visualizations, please download the code and run it on your local machine.

# Anime Recommendation Dataset

This repository contains two datasets related to anime shows and user ratings:

## anime-filtered.csv

Based on 2021 data, this dataset contains information about various anime shows. Here's a brief overview of the dataset:

| Column Name | Description |
| --- | --- |
| `anime_id` | The unique identifier for each anime show. |
| `Name` | The title of the anime show, in both English and Japanese. |
| `Score` | The average rating score of the anime show. |
| `English name` | The English title of the anime show. |
| `Japanese name` | The Japanese title of the anime show. |
| `synopsis` | A brief summary of the storyline or plot of each anime. |
| `Type` | The format of the anime show, such as TV series, movie, or other. |
| `Episodes` | The total number of episodes for each anime show. |
| `Aired` | The date range when the anime aired. |
| `Premiered` | The specific season and year of the anime's premiere. |
| `Producers` | The companies involved in producing the anime. |
| `Licensors` | The companies involved in distributing the anime. |
| `Studios` | The animation studios that produced the anime. |
| `Source` | The medium from which the anime was adapted, such as manga or original. |
| `Duration` | The length of each episode. |
| `Rating` | The target audience rating for the anime. |
| `Ranked` | The popularity rank of the anime. |
| `Popularity` | The popularity rank of the anime. |
| `Members` | The number of members who have the anime in their list. |
| `Favorites` | The number of users who have marked the anime as their favorite. |
| `Watching` | The number of users who are currently watching the anime. |
| `Completed` | The number of users who have completed watching the anime. |
| `On-Hold` | The number of users who have put the anime on hold. |
| `Dropped` | The number of users who have dropped the anime. |

## user-filtered.csv

Based on 2021 data, this dataset contains information about user rating on each anime. Here's a brief overview of the dataset:

| Column Name | Description |
| --- | --- |
| `user_id` | The unique identifier for each user. |
| `anime_id` | The unique identifier for each anime show. |
| `rating` | The user's rating for the anime on a scale from 0 to 10, with 10 being the highest rating. |

These datasets provide valuable information for analyzing and understanding the characteristics, ratings, popularity, and viewership of different anime shows, as well as user preferences and ratings for various anime shows.

## Acknowledgments

I would like to express my gratitude to the following sources for their contributions to this dataset:

- Kaggle: Anime Recommendation Database, MyAnimeList Dataset - This dataset served as the basis for my analysis and recommendation system project. I would like to thank the contributors who originally collected and shared this dataset, as it provided valuable insights and data for my research.
- MyAnimeList - I am grateful to the platform for hosting the original data and providing a comprehensive database of anime titles and user ratings. Their platform has been an invaluable resource for anime enthusiasts and researchers alike.
## Dataset Source

The dataset was obtained from [MyAnimeList](https://myanimelist.net/), a popular anime and manga database. You can get the data from [Anime Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset), which provides access to the database's anime and manga information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
