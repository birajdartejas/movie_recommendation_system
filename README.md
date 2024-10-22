# movie_recommendation_system
![Screenshot 2024-10-22 234435](https://github.com/user-attachments/assets/f1397733-c3b9-4262-9655-69d68b857275)
# Movie Recommendation System 🎥

This is a **Movie Recommendation System** built using **Machine Learning**. The system uses collaborative filtering and content-based filtering methods to recommend movies to users based on their preferences and past behaviors.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)





## Features
- Recommends movies based on:
  - Similar movies that a user has rated highly
  - Content-based recommendations using movie genres, cast, and descriptions
- Collaborative filtering using user ratings
- Search functionality for finding movies
- Responsive web interface

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask or Django)
- **Machine Learning**: Scikit-Learn, Pandas, NumPy
- **Database**: SQLite or any other DBMS
- **Deployment**: Heroku / AWS / Docker

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/birajdartejas/MovieRecommendation.git
    cd MovieRecommendation
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use: env\Scripts\activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Navigate to `http://localhost:5000` in your browser to access the application.

## Usage

- Input the name of the movie you want recommendations for.
- The system will return a list of movies that are similar or recommended based on your search.
- You can filter recommendations based on genres, user ratings, or year of release.

