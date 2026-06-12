# Social Network Data Analysis Using Python

A comprehensive Python project that analyzes social network data, including data cleaning, structuring, and generating recommendations based on user relationships.

## Project Overview

This project provides tools and analysis for social network data with the following features:
- **Data Loading and Exploration**: Readable data format analysis
- **Data Cleaning & Structuring**: Processing and organizing raw data
- **People You May Know**: Algorithm to suggest potential connections
- **You Might Like**: Content recommendation system based on social connections

## Notebooks

1. **1_humanreadable_data.ipynb** - Data exploration and readable format analysis
2. **2_cleaning_structuring_data.ipynb** - Data cleaning and preprocessing
3. **3_people_you_may_know.ipynb** - Friendship recommendation algorithm
4. **4_you_might_like.ipynb** - Content/interest recommendation system

## Data Files

- `data.json` - Processed social network data
- `massive_data.json` - Extended dataset for large-scale analysis

## Features

### People You May Know
Suggests potential friends based on mutual connections:
- Analyzes direct friend relationships
- Counts mutual connections
- Ranks suggestions by connection strength

### You Might Like
Recommends content or interests based on:
- Friends' preferences
- Similar user connections
- Social clustering

## Requirements

- Python 3.x
- Jupyter Notebook
- JSON library (built-in)

## Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/social-network-data-analysis-using-python.git
cd social-network-data-analysis-using-python
```

2. Open Jupyter Notebook:
```bash
jupyter notebook
```

3. Run the notebooks in order:
   - Start with `1_humanreadable_data.ipynb`
   - Continue with `2_cleaning_structuring_data.ipynb`
   - Explore `3_people_you_may_know.ipynb`
   - Check `4_you_might_like.ipynb`

## How It Works

### People You May Know Algorithm
```
For each user:
1. Get all direct friends
2. For each friend, get their friends
3. Count how many mutual connections each person has
4. Exclude the user themselves and current friends
5. Rank by mutual connection count
6. Return sorted list of suggestions
```

## License

This project is open source and available under the MIT License.

## Author

Coders of Delhi

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
