# Steam Data Visualization Dashboard

Interactive Streamlit app for exploring a game store dataset using rich Plotly visualizations and practical filters. The dashboard surfaces insights across downloads, ratings, pricing, tags, and platform/language support.

## Features

- Sidebar filters: tags, developers, minimum downloads, release year range, free-only, OS, languages, and top-N.
- 16+ visualizations including advanced types: treemap, sunburst, parallel coordinates, sankey, network, marimekko, 3D scatter, density heatmap, icicle.
- Consistent labeling, hover tooltips, zoom/pan, and color scales for interpretability.
- Performance optimization: heavy charts render the top 50 rows by `estimated_downloads`.

## Dataset

- File: `data/bestSelling_games.csv`
- Columns used: `game_name`, `developer`, `release_date`, `release_year`, `estimated_downloads`, `all_reviews_number`, `reviews_like_rate`, `rating`, `price`, `difficulty`, `length`, `age_restriction`, `user_defined_tags`, `supported_os`, `supported_languages`, `other_features`, `is_free`.
- Ensure the dataset meets course requirements (≥ 2,000 rows, ≥ 7 columns).

## Quick Start

1. Install Python 3.10+.
2. Install dependencies:
   ```bash
   pip install streamlit plotly pandas numpy
   ```
3. Run the app:
   ```bash
   streamlit run trae_app.py
   ```

## Visualizations

- Bar chart
- Treemap
- Parallel coordinates
- Scatter/Bubble
- Sunburst
- Hetmanp
- Line chart
- 3D scatter
- Icicle
