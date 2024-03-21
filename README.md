# No-SQL

***Eat Safe, Love***


The NoSQL_setup.ipynb sets up and updates the database. The NoSQL_analysis.ipynb queries relevant information for analyses and converts results into Pandas DataFrame. 

The data given in the establishments.json file was imported using Terminal with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json.


***Analysis***

-Which establishments have a hygiene score equal to 20?

-There are 41 establishments with a hygiene score of 20 from the uk_food dataset.

-Which establishments in London have a RatingValue greater than or equal to 4?

-There are 34 establishments in London that have a RatingValue greater than or equal to 4 from the uk_food dataset.

-What are the top 5 establishments with a RatingValue rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

-The top 5 establishments with a RatingValue of '5' sorted by lowest hygiene score nearest to "Penang Flavours" are: "Volunteer", "Plumstead Manor Nursery", "Atlantic Fish Bar", "Iceland", and "Howe and Co Fish and Chips - Van 17".

-How many establishments in each Local Authority area have a hygiene score of 0?

-There are 55 rows in the DataFrame. This is the preview of the first 10 rows:

![nosql](https://github.com/jirah2018/No-SQL/assets/151040384/9e7c16bd-8c70-487d-bb2d-42ec8dc07173)

