raw laptop data.csv :- 
It is a CSV file containing the essential data regarding all the laptops present in the market. The raw data consists of features like :-
1. Company
2. TypeName
3. Inches
4. Screen Resolution
5. CPU
6. Ram
7. Memory
8. GPU
9. OS
10. Weight
11. Price

laptopdata.sql :-
Is a SQL file containing SQL queries highlighting the techniques implemented to clean the data, reduce noise in the data and feature engineering for establishing more impactful patterns.
Some of the feature engineeing that I had done is as :-
1. Screen Resoultion = W X H
   Resoltuion_width = W
   Resoltion_height = H
2. CPU => CPU_brand + CPU_name + CPU_speed
3. Memeory => Memory_Type + primary_memory + secondary_memory
4. GPU => GPU_brand
5. A new feature is created based on the Screen Type. Whether the screen is touch sensitive or not?

cleaned_laptopdata.csv
Is another CSV file but it contains the cleaned engineered data. The cleaned data finally contains features like
1. Company
2. TypeName
3. Inches
4. resolution_width
5. resolution_height
6. TouchScreen
7. cpu_brand
8. cpu_speed
9. Ram
10. Memory_type
11. primary_memory
12. secondary_memory
13. GPU_brand
14. OS
15. Weight
16. Price

Exploratory Data Analysis :-
Which features of a Laptop directly affects its price?
