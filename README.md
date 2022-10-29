# PyBer_Analysis

## Analysis
The purpose of this analysis was to understand how to use the Pandas, Numpys, and Matplotlib libraries functions in Jupyter notebook. 
In Deliverable 1, we were able to creat a Pyber summary of by type for rural, suburban, and urban sections. 

![image](https://user-images.githubusercontent.com/111409181/198527902-d7950522-534c-4b99-91e7-2d063d1d28af.png)


For Step 8, we cleaned the data to added the format of $ for the fares. 

![image](https://user-images.githubusercontent.com/111409181/198528613-e8d3a6cd-2fd6-4a1f-9c00-cce5d6e55da0.png)


In Deliverable 2 we used the groupby funtion and pivot function to create the date into an index, the cities into a type, and the fares into a value.
after creating that dataframe the spots with no fares with given NaN in their cells. I ended up getting the data from the first 5 and last 5 of entire date. But then re-did the code doing head(10) to match the data table set in the challenge question. 

![image](https://user-images.githubusercontent.com/111409181/198817422-d77ceadf-7422-4668-90db-da71c7a1c1a1.png)


In step 7 we did a resample function by adding 'W' for weeks. the result of the datafram was this. 


![image](https://user-images.githubusercontent.com/111409181/198817325-53bb32cb-8be3-42e8-a654-a2f8ab344e96.png)

Then finally in step 8 when we were plotting to create the chart. I inittially had it wrong then firgured out that I forgot to import the numpy function and use it as part of the yticks for the chart anylysis. By correcting that part of the code, I was able to get the chart to closely resemble the one that was shown in the challnge. 

![image](https://user-images.githubusercontent.com/111409181/198817585-a8b6e225-eb53-4761-aed4-25fe6af755ef.png)

By leanring and being able to apply this functions in class we were able to figure out the fares between the cities or urban. suburban, and rural cities. 
based on the results of the chart it shows that the the urban cities are performing at a better pace than compared to suburban and rural city fares. 
