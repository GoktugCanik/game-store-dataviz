# Steam Games Data Visualization Dashboard

## Dataset

Source file: `data/bestSelling_games.csv` , [Kaggle ling](https://www.kaggle.com/datasets/hbugrae/best-selling-steam-games-of-all-time)

Key fields: `game_name`, `developer`, `release_date/year`, `estimated_downloads`, `all_reviews_number`, `reviews_like_rate`, `rating`, `price`, `difficulty`, `length`, `age_restriction`, `user_defined_tags`, `supported_os`, `supported_languages`

## Goals

Build an interactive dashboard to explore trends and relationships across the game catalog.

Provide clear insights with advanced visualizations and practical interactivity.

## Techniques & Interactivity

Visualizations: treemap, sunburst, parallel coordinates, 3D scatter, heatmap, icicle, bar, line, bubble.

Interactivity: sidebar filters for tags, developers, inimum downloads, release year range, free-only, OS, languages; tooltips; zoom/pan; color highlighting.Scatter/Bubble

## Key Insights (Illustrative)

Downloads and ratings: `rating` correlates with `estimated_downloads` up to mid-high ranges; extreme values may reflect niche titles.

Price and rating: moderate prices often cluster near mid-to-high ratings; very high prices can show polarized ratings.

Tags and age groups: certain tags concentrate within specific age restrictions; stacked shares vary across developers.

Platforms and languages: Windows support dominates; language distribution is skewed toward a few widely-supported languages.

## Repository

Repo: https://github.com/GoktugCanik/game-store-dataviz.git.
