# nosql-challenge

## `NoSQL_setup_starter.ipynb`

- Imports `establishments.json` into MongoDB, creating the `uk_food` database and `establishments` collection.
- Establishes a connection to MongoDB using PyMongo.
- Code to verify correct data import into the database.
- Adds "Penang Flavours" restaurant to the database.
- Updates `BusinessTypeID` for the new restaurant.
- Removes establishments in the Dover Local Authority area.
- Converts data fields like latitude, longitude, and `RatingValue` from strings to numeric types.

## `NoSQL_analysis_starter.ipynb`

- Connects to the `uk_food` database and accesses the `establishments` collection. 
- Identifies establishments with specific hygiene scores.
- Filters establishments in London based on `RatingValue`.
- Determines top 5 establishments with the highest `RatingValue`, nearest to "Penang Flavours".
- Uses aggregation to count establishments with a hygiene score of 0 in each Local Authority area.

## Resources used

- "https://www.w3schools.com/python/python_json.asp"
