# Mood-Based Music Recommender 🎶

This project implements a **mood-based music recommender system** using
Natural Language Processing (NLP) and Spotify datasets.\
It analyzes a user's mood description (text input), detects sentiment,
and recommends suitable **music genres**.

## 📌 Project Overview

-   Uses **TextBlob** for sentiment polarity analysis.
-   Accepts user input (free text or sample options) and detects mood
    (happy, sad, neutral, angry, excited, relaxed).
-   Matches mood with Spotify genres based on valence and energy
    attributes.
-   Interactive interface built with **ipywidgets**.

## 📂 Datasets Used

The following datasets are required and used in this notebook: -
`data_by_genres.csv` - `data_w_genres.csv`

These datasets contain Spotify audio features aggregated by genres and
tracks with genre tags.

## ⚙️ Technologies Used

-   Python 3
-   Pandas
-   TextBlob
-   ipywidgets
-   Jupyter Notebook

## 🚀 How to Run

1.  Clone this repository:

    ``` bash
    git clone https://github.com/MuhammadAsad29/mood-based-music-recommender
    cd music-mood-recommender
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

3.  Launch the notebook:

    ``` bash
    jupyter notebook mood_music_recommender.ipynb
    ```

## 🎯 Features

-   Detects mood using sentiment analysis and keyword matching.
-   Provides **emoji feedback**, motivational messages, and suggested
    genres.
-   Interactive UI with **widgets** (input box, dropdown, live
    re-analysis).

## 📝 Author

Developed by Muhammad Asad.
