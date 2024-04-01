# data-sourcing-challenge
## Overview
This project extracts and merges movie review data from The New York Times and The Movie Database (TMDb) APIs, preparing it for use in a recommendation system.

## Setup
- **Dependencies**: Python 3.x, Jupyter Notebook, Pandas, Requests, Python-dotenv.
- **API Keys**: Store your New York Times and TMDb API keys in a `.env` file with variables `NYT_API_KEY` and `TMDB_API_KEY`.

## Running the Notebook
1. Install dependencies: `pip install pandas requests python-dotenv`.
2. Launch Jupyter Notebook: `jupyter notebook`.
3. Open and run `retrieve_movie_data.ipynb`.

## Structure
1. **NYT API Access**: Fetches movie reviews.
2. **TMDb API Access**: Fetches movie details.
3. **Data Merge & Clean**: Combines and cleans data for export.

## Output
- **File**: `collected_data.csv` in the `output` directory contains the prepared data.

## Note
Ensure the `.env` file with your API keys is in the same directory as the notebook.
This version retains the essential information while being more succinct, suitable for a quick overview.

## References
Based on starter files and data provided as part of OSU-VIRT-AI-PT-02-2024-U-LOLC-MTTH (OSU AI Bootcamp) for Challenge 4. Remaining code based on code examples provided as part of the course.