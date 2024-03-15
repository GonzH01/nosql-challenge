#### Overview
The project's main purpose is to analyze UK food hygiene ratings to guide "Eat Safe, Love" magazine in selecting establishments for review. It involves setting up a database, importing and updating data, and conducting detailed analyses to find establishments of interest.

#### Part 1: Database Setup (`NoSQL_setup_starter.ipynb`)
This notebook guides the initial setup of the database and ensures data is properly loaded.

##### Steps:
1. **Data Import**: Use `establishments.json` to create the `uk_food` database and `establishments` collection.
2. **Library Import**: Import necessary Python libraries like PyMongo and Pretty Print (pprint).
3. **Mongo Client**: Create an instance of the Mongo Client for database interaction.
4. **Database Confirmation**: Verify the creation of the database and loading of data.
5. **Variable Assignment**: Assign the `establishments` collection to a variable for easier use.

#### Part 2: Database Update (`NoSQL_setup_starter.ipynb`)
This section involves modifying the database based on specific requirements from the magazine editors.

##### Modifications:
1. **Add New Restaurant**: Insert a new halal restaurant, "Penang Flavours", in Greenwich.
2. **BusinessTypeID Update**: Find and update the BusinessTypeID for "Restaurant/Cafe/Canteen".
3. **Remove Dover Establishments**: Identify and delete establishments in the Dover Local Authority.
4. **Data Type Correction**: Convert latitude, longitude, and RatingValue to appropriate data types.

#### Part 3: Exploratory Analysis (`NoSQL_analysis_starter.ipynb`)
The analysis aims to answer specific questions from the magazine editors about food establishments.

##### Analysis Tasks:
1. **Hygiene Score Inquiry**: Identify establishments with a hygiene score of 20.
2. **London Establishments Rating**: Find London establishments with a RatingValue of ≥ 4.
3. **Top 5 Establishments Near Penang Flavours**: Locate the top 5 establishments with a RatingValue of 5, closest to "Penang Flavours".
4. **Hygiene Score by Local Authority**: Determine the number of establishments in each local authority with a hygiene score of 0, sorted from highest to lowest.
