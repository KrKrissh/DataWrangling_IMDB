# DataWrangling_IMDB

A Dataset is given which contains informations about movies. 
This Dataset has been imported from google drive using library google.colab

Below is a part of the informations given :

            <class 'pandas.core.frame.DataFrame'>
            RangeIndex: 3000 entries, 0 to 2999
            Data columns (total 23 columns):
             #   Column                 Non-Null Count  Dtype  
            ---  ------                 --------------  -----  
             0   id                     3000 non-null   int64  
             1   belongs_to_collection  604 non-null    object 
             2   budget                 3000 non-null   int64  
             3   genres                 2993 non-null   object 
             4   homepage               946 non-null    object 
             5   imdb_id                3000 non-null   object 
             6   original_language      3000 non-null   object 
             7   original_title         3000 non-null   object 
             8   overview               2992 non-null   object 
             9   popularity             3000 non-null   float64
             10  poster_path            2999 non-null   object 
             11  production_companies   2844 non-null   object 
             12  production_countries   2945 non-null   object 
             13  release_date           3000 non-null   object 
             14  runtime                2998 non-null   float64
             15  spoken_languages       2980 non-null   object 
             16  status                 3000 non-null   object 
             17  tagline                2403 non-null   object 
             18  title                  3000 non-null   object 
             19  Keywords               2724 non-null   object 
             20  cast                   2987 non-null   object 
             21  crew                   2984 non-null   object 
             22  revenue                3000 non-null   int64  
            dtypes: float64(2), int64(3), object(18)
            memory usage: 539.2+ KB
            



What we have to do is to first perform Check on Data Sanity.
Then we have to perform various operations like :
### Which movie made the highest profit? Who were its producer and director? Identify the actors in that film.
### This data has information about movies made in different languages. Which language has the highest average ROI (return on investment)?
### Find out the unique genres of movies in this dataset.
### Make a table of all the producers and directors of each movie. Find the top 3 producers who have produced movies with the highest average RoI?
### Which actor has acted in the most number of movies? Deep dive into the movies, genres and profits corresponding to this actor.
### Top 3 directors prefer which actors the most?



Python language has been used to solve this problem.
Various libraries used to solve this problem are :
        Pandas, NumPy, google.colab.drive, 
