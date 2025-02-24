# Movie Recommendation System

## Overview
This is a **Movie Recommendation System** built using **Machine Learning**. It suggests movies based on the similarity between them, helping users find movies they might enjoy based on their preferences.

## Features
- Uses **content-based filtering** to recommend similar movies.
- Reads movie data from a CSV file.
- Finds the most similar movies based on user input.

## Technologies Used
- **Python**
- **Pandas**
- **Difflib** (for finding close matches)
- **Pickle** (for loading the similarity matrix)
- **Sklearn** (for vectorizing and cosine similarity)

## Installation
### 1. Clone the Repository
```sh
git clone https://github.com/your-username/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

## Usage
1. Ensure that the `movies.csv` file is present in the `src/` directory.
2. Run the script:
```sh
python recommend.py
```
3. Enter a movie name when prompted.
4. The system will return a list of similar movies.


## Example Output
```
Enter your favorite movie: Inception

1. Interstellar - Score: 0.92
2. The Prestige - Score: 0.89
3. The Dark Knight - Score: 0.87
...
```

## Contribution
Feel free to contribute by submitting a pull request or reporting issues!


