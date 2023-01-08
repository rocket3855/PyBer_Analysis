# PyBer_Analysis
  
# Deliverable 1
  1. Download the PyBer_Challenge_starter_code.ipynb file into your PyBer_Analysis folder and rename it         PyBer_Challenge.ipynb. 
      - Completed
  
  2. Use the step-by-step instructions below to add code where indicated by the numbered comments in the       starter code file.
      - Completed

  3. In Step 1, use the groupby() function to create a Series of data that has the type of city as the       index,   then apply the count() method to the "ride_id" column.
      - Completed

  4. In Step 2, use the groupby() function to create a Series of data that has the type of city as the       index,   then apply the sum() method to the "driver_count" column.
      - Completed

  5. In Step 3, use the groupby() function to create a Series of data that has the type of city as the       index,   then apply the sum() method to the "fare" column.
      - Completed

  6. In Step 4, calculate the average fare per ride by city type by dividing the sum of all the fares by     the   total rides.
      - Completed
  7. In Step 5, calculate the average fare per driver by city type by dividing the sum of all the fares by     the total drivers.
      - Completed
  8. In Step 6, create a PyBer summary DataFrame with all the data gathered from Steps 1-5, using the         column   names shown below:
      - Completed

  9. In Step 7, use the provided code snippet to remove the index name ("type") from the PyBer summary         DataFrame.
     - Completed
  10. In Step 8, format the columns of the Pyber summary DataFrame 
      - Completed

# Deliverable 2
  1. In Step 1, create a new DataFrame with multiple indices using the groupby() function on the "type" and     "date" columns of the pyber_data_df DataFrame, then apply the sum() method on the "fare" column to show      the total fare amount for each date.
  2. In Step 2, use the provided code snippet to reset the index. This is needed to use the pivot()             function in the next step (Step 3).
  3. In Step 3, use the pivot() function to convert the DataFrame from the previous step so that the index    is the "date," each column is a city "type," and the values are the "fare."
   3a. After this step, you’ll see that each cell has the total fare for the date and time, as shown in the     following image.
   4. In Step 4, create a new DataFrame by using the loc method on the following date range: 2019-01-01         through 2019-04-28.
   5. In Step 5, use the provided code snippet to reset the index of the DataFrame from the previous step       (Step 4) to a datetime data type. This is necessary to use the resample() method in Step 7.
   6. In Step 6, use the provided code snippet, df.info(), to check that the "date" is a datetime data          type.
   7. In Step 7, create a new DataFrame by applying the resample() function to the DataFrame you modified       in Step 5. Resample the data in weekly bins, then apply the sum() method to get the total fares for e       each week.

# Deliverable 3: Written Report


