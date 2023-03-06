# nosql-challenge

Part 1: Database and Jupyter Notebook

In the <NoSQL_setup_starter.ipynb> file, data from the <establishments.json> file was imported. The database is named uk_food and the collection is named establishments. All other requirements for the jupyter notebook setup were complete and can be found in the jupyter notebook setup file.

Part 2: Update the Database

In the <NoSQL_setup_starter.ipynb> file:

    The supplied data for Penang Flavours restaurant inserted into the establishments collection.
    39779 documents changes to 39780.
    The Penang Flavours restaurant has the correct value for the Business Type ID (1) updated.
    All documents in the collection where the value of Dover for the Local Authority Name are removed.
    A total of 994 documents is removed from the collection, reducing the database to 38786 documents.
    Latitude and Longitude values have been converted from a string to decimal numbers.

Part 3: Exploratory Analysis

In the <NoSQL_analysis_starter.ipynb>


    Question 1. 41 establishments with a hygiene score equal to 20.
                Converted to a pandas DataFrame, displaying first 10 rows.

    Question 2. 34 establishments in London with a RatingValue greater than or equal to 4.
                Converted to a pandas DataFrame, displaying first 10 rows.

    Question 3. The top 5 establishments, with a rating Value of 5, sorted by lowest hygiene score 
                and within 0.01 degree of the Penang Flavours restaurant.
                Converted to a pandas DataFrame.

    Question 4. 55 Local Authorities, Hygiene score 0.
                Each with a varying count of restaurants in the area.

                An aggregation pipeline was built to match the query of finding:
                establishments in each Local Authority area that have a hygiene score of 0, 
                grouped and a count of the number of restaurants in the area, sorted in descending order.
                Converted to a pandas DataFrame, displaying the first 10 results.
                The first 5 rows match data provide on bootcamp spot.

I have also done my best to comment concisely and use relevant notes that other developers can understand.