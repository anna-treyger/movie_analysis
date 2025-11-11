# popcorn_consulting

The .ipynb file contains the starting code and primary tasks for starting the project.

```python
import pandas as pd
import numpy as np
import os

# Change OS directory to match wherever you downloaded the files

os.chdir("C:\\Users\\Anna\\Downloads")

df_1 = pd.read_csv("movies_data\\tmdb_5000_movies.csv")
df_2 = pd.read_csv("movies_data_2\\TMDB_movie_dataset_v11.csv")

print("Movie Dataset 1:\n")
print(df_1.head())
print("Movie Dataset 2:\n")
print(df_2.head())

# Current Tasks:
# 1) Clean each dataset to only include relevant info: budget, genres, language, **title**, release date, revenue, runtime
# 2) Rename any columns to prepare for merging
# 3) Merge datasets on "title"
```

**Links to the datasets:**

**Dataset 1**

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

**Dataset 2**

https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data?select=TMDB_movie_dataset_v11.csv
