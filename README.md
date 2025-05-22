## Objective
I want to use this repository to upload my projects.
My goal is to use a dataset to practice analysis and reporting in Excel.  

# Why did I choose this dataset?
- To identify the makes and models with the highest units sold.

# Implications and Use Cases:
- Helps buyers and sellers understand current market trends.
- For buyers, a popular vehicle suggests a more liquid market, making it easier to resell.


## Dataset Used 
- [Vehicle Sales Data](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data)

## References 
- [Full Project in Excel | Excel Tutorials for Beginners](https://www.youtube.com/watch?v=opJgMj1IUrc&ab_channel=AlexTheAnalyst)

## Step 1: Cleaning and Transformation
- I created the 'Working Sheet,' 'Pivot Table,' and 'Dashboard' sheets while keeping the raw data in 'car_prices' unchanged.
- With the 'Working Sheet' I removed the duplicates.

![image](https://github.com/user-attachments/assets/3de1da66-8889-49db-bdad-a7e79a8402b5)

- Then, I converted the raw data into a table. 

# Added Vehicle Condition Grades
![image](https://github.com/user-attachments/assets/d1f1a4d0-c652-46f4-8845-49af8234bf13)


I added the 'Condition Brackets' column and used the IF function to assign condition grades to each sold vehicle.
- Between 49 to 40 = "Excellent" 
- Between 39 to 30 = "Great" 
- Between 29 to 20 = "Good" 
- Between 19 to 10 = "Fair" 
- Between 9 to 1 = "Poor" 
- 0 values were assigned "N/A"

## PivotTable
- 
