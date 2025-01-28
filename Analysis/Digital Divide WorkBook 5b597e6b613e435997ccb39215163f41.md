# Digital Divide WorkBook

Using the following CSV

[school_broadband_data.csv](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/school_broadband_data.csv)

[digital_divide_2024.ipynb](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/digital_divide_2024.ipynb)

Data.Describe()

[Out_6__sort_index_ascending_False.json](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Out_6__sort_index_ascending_False.json)

1. **Standard Deviation (std)**: This tells us how much the numbers differ from the average value.
    - **Zipcode**: Zip codes vary by about 121.
    - **Average_Rating**: School ratings differ by about 2.1 points.
    - **Sum_Awards**: The total awards per area differ by about 1.4.
    - **Num_Public/Num_Private**: The number of public and private schools per area varies by about 1.4.
    - **Sum_Students**: The total number of students per area differs by about 1093.
    - **Sum_Teachers**: The total number of teachers per area differs by about 90.
    - **Student_Teacher_Ratio**: The student-teacher ratio varies by about 29.
    - **Public_Rating**: Public school ratings vary by about 4.6 points.
    - **Public_Awards**: Public school awards vary by about 1.4.
    - **Median/Mean income**: Median family income differs by about $49,886, and the mean (average) income differs by about $71,783.
    - **Total Families**: The number of families in each area varies by about 3004.
    - **Internet Access**: Various internet subscription types have different levels of variability.
2. **Minimum Value (min)**: This shows the smallest number in each category.
    - **Zipcode**: The lowest zip code is 2115.
    - **Average_Rating**: The lowest school rating is 1.
    - **Sum_Awards**: Some areas have no awards.
    - **Num_Public/Num_Private**: Some areas have no public or private schools.
    - **Sum_Students/Sum_Teachers**: The smallest student body is 56, and some areas have no teachers.
    - **Student_Teacher_Ratio**: The smallest ratio is 6.
    - **Median/Mean Income**: The lowest median income is $51,214, and the lowest mean income is $69,203.
    - **Total Families**: The smallest number of families is 1572.
    - **Internet Access**: Some areas have no computers or internet access.
3. **Mean Value (mean)**: This is the average number.
    - **Zipcode**: The average zip code is around 2185.
    - **Average_Rating**: The average school rating is about 3.8.
    - **Sum_Awards**: The average number of awards is 0.75.
    - **Num_Public/Num_Private**: On average, there are about 1.7 public and 1.6 private schools.
    - **Sum_Students/Sum_Teachers**: The average student body is about 1424, and the average number of teachers is about 94.
    - **Student_Teacher_Ratio**: The average ratio is 21.
    - **Median/Mean Income**: The average median income is about $117,994, and the average mean income is about $161,194.
    - **Total Families**: The average number of families is about 6003.
    - **Internet Access**: Most areas have high computer and broadband access.
4. **Maximum Value (max)**: This shows the largest number in each category.
    - **Zipcode**: The highest zip code is 2472.
    - **Average_Rating**: The highest school rating is 8.
    - **Sum_Awards**: Some areas have up to 4 awards.
    - **Num_Public/Num_Private**: Some areas have up to 5 public and 5 private schools.
    - **Sum_Students/Sum_Teachers**: The largest student body is 4760, and the highest number of teachers is 393.
    - **Student_Teacher_Ratio**: The highest ratio is 155.
    - **Median/Mean Income**: The highest median income is $222,522, and the highest mean income is $349,493.
    - **Total Families**: The largest number of families is 13710.
    - **Internet Access**: The highest number of computers and broadband subscriptions is very high.
5. **Count (count)**: This shows how many entries there are for each category. Here, most categories have 32 entries, meaning there are 32 areas in this data set.
6. **75% Percentile (75%)**: This shows the value below which 75% of the data falls.
    - **Zipcode**: 75% of zip codes are below 2149.
    - **Average_Rating**: 75% of school ratings are below 5.25.
    - **Sum_Awards**: 75% of areas have 0.5 or fewer awards.
    - **Num_Public/Num_Private**: 75% of areas have up to 2.25 public and 3 private schools.
    - **Sum_Students/Sum_Teachers**: 75% of student bodies are below 2018, and 75% of teacher numbers are below 136.
    - **Student_Teacher_Ratio**: 75% of student-teacher ratios are below 17.
    - **Median/Mean Income**: 75% of median incomes are below $153,093, and mean incomes below $194,107.
    - **Total Families**: 75% of areas have fewer than 6962 families.
    - **Internet Access**: 75% of areas have fewer computers and broadband subscriptions compared to the highest 25%.
7. **50% Percentile (Median)**: This is the middle value, where half the data is above and half is below.
    - **Zipcode**: The median zip code is 2134.
    - **Average_Rating**: The median school rating is about 3.8.
    - **Sum_Awards**: The median number of awards is 0.
    - **Num_Public/Num_Private**: The median number of public and private schools is 1 each.
    - **Sum_Students/Sum_Teachers**: The median student body is 1262, and the median number of teachers is 81.
    - **Student_Teacher_Ratio**: The median ratio is 13.
    - **Median/Mean Income**: The median median income is $117,033, and the median mean income is $156,851.
    - **Total Families**: The median number of families is about 5942.
    - **Internet Access**: The median number of computers and broadband subscriptions is high.
8. **25% Percentile (25%)**: This shows the value below which 25% of the data falls.
    - **Zipcode**: 25% of zip codes are below 2125.
    - **Average_Rating**: 25% of school ratings are below 1.75.
    - **Sum_Awards**: 25% of areas have 0 awards.
    - **Num_Public/Num_Private**: 25% of areas have 1 public and 1 private school or fewer.
    - **Sum_Students/Sum_Teachers**: 25% of student bodies are below 567, and 25% of teacher numbers are below 26.
    - **Student_Teacher_Ratio**: 25% of student-teacher ratios are below 8.
    - **Median/Mean Income**: 25% of median incomes are below $55,587, and mean incomes below $81,431.
    - **Total Families**: 25% of areas have fewer than 2561 families.
    - **Internet Access**: 25% of areas have fewer computers and broadband subscriptions compared to the highest 75%.

This data helps us understand the spread and average conditions of schools, family incomes, and internet access across different areas.

Have to standardize my data

[Standardization](https://www.notion.so/Standardization-79c30d353b48425486c3dcf7b7885c81?pvs=21)

Sure! Here are your points formatted as bullet points:

- Average_Rating
- Sum_Awards
- Num_Public
- Num_Private
- Sum_Students
- Sum_Teachers
- Student_Teacher_Ratio
- Private_Awards
- Public_Awards
- Private_Rating
- Public_Rating
- Private_School_Students
- Public_School_Students
- Total_Families
- Total!!Less than $10,000_Families
- Total!!$10,000 to $14,999_Families
- Total!!$15,000 to $24,999_Families
- Total!!$25,000 to $34,999_Families
- Total!!$35,000 to $49,999_Families
- Total!!$50,000 to $74,999_Families
- Total!!$75,000 to $99,999_Families
- Total!!$100,000 to $149,999_Families
- Total!!$150,000 to $199,999_Families
- Total!!$200,000 or more_Families
- Median income (dollars)_Families
- Mean income (dollars)_Families
- Total:!!Has a computer:
- Total:!!Has a computer:!!With dial-up Internet subscription alone
- Total:!!Has a computer:!!With a broadband subscription:
- Total:!!Has a computer:!!With a broadband subscription:!!With a fixed broadband Internet subscription:
- Total:!!Has a computer:!!With a broadband subscription:!!With a fixed broadband Internet subscription:!!With a cellular data plan
- Total:!!Has a computer:!!With a broadband subscription:!!With a fixed broadband Internet subscription:!!Without a cellular data plan
- Total:!!Has a computer:!!With a broadband subscription:!!Cellular data plan alone or with dial-up
- Total:!!Has a computer:!!Without Internet subscription
- Total:!!No Computer
- public + private ratio

[Histograms Versus Scatterplots](https://www.notion.so/Histograms-Versus-Scatterplots-806b6cdc19d544069bdc49a4d46b5528?pvs=21)

### HISTOGRAMS

1. **Distribution of Ratings**
    - **Column**: `Average_Rating`
    
    ![Distribution_Average_Rating.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Distribution_Average_Rating.png)
    
    - **Findings**: Right-skewed. Most zipcodes have a low concentration of schools that are highly rated. However, it seems that zipcodes either have schools with a lot of good ratings or a lot of bad. There are few zipcodes that have a high concetration of schools with mid ratings.
2. **Distribution of Awards**
    - **Columns**: `Sum_Awards`, `Private_Awards`, `Public_Awards`
    
    ![Distribution_Total_Awards.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Distribution_Total_Awards.png)
    
    - **Findings**: Only did Sum Awards. Right-skewed, 0 awards is the most popular
    - I’m not sure awards is something schools really count/keep track of.
3. **Income Distribution of Families**
    - **Columns**: `Median income (dollars)_Families`, `Mean income (dollars)_Families`
    
    ![Distribution_Median_Income.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Distribution_Median_Income.png)
    
    ![Distribution_Mean_Income.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Distribution_Mean_Income.png)
    
    - **Findings**: Both are right-skewed. Most Massachusettes zipcodes have a low mean/median for familial income.
4. **Broadband Subscription Distribution**
    - **Columns**: `Total:!!Has a computer:!!With a broadband subscription:`
    
    ![Distribution_Computer_Broadband.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Distribution_Computer_Broadband.png)
    
    - **Findings**: Right-skewed. Most zipcodes contain a low concentration of families that have a broadband subscription.
    
    ### Scatterplots
    
    1. **Average Rating vs. Broadband Subscription**
        - **X-axis**: `Average_Rating`
        - **Y-axis**: `Total:!!Has a computer:!!With a broadband subscription:`
        
        ![Average_Rating__Broadband.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Average_Rating__Broadband.png)
        
        - **Findings: I**nverse correlation. Areas with higher broadband access tend to have lower school ratings, and areas with lower broadband access tend to have higher school ratings.’
        - This might suggest that having more broadband does not equate to better educational outcomes/quality. Since this seems to prove contrary to my hypothesis.
    2. **Public vs. Private School Ratings**
        - **X-axis**: `Private_Rating`
        - **Y-axis**: `Public_Rating`
        
        ![Private_PublicRating.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Private_PublicRating.png)
        
        - **Findings:** Literally no idea what this means
        
        The following is an assortment of scatterplots between Income Levels and Internet Access 
        
        I have picked out the most interesting ones for viewing on this page
        

[Scatterplots $ x internet](https://www.notion.so/Scatterplots-x-internet-f91ffc5d290744cf89e2faa12f46a692?pvs=21)

![Total_$10,000_to_$14,999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Scatterplots%20$%20x%20internet%20f91ffc5d290744cf89e2faa12f46a692/Total_10000_to_14999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning between $10,000 and $15,000 increases in a given zip code, the number of households with computers but no internet subscription also tends to increase.

![Total_$10,000_to_$14,999_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_10000_to_14999_Families_vs_Total_No_Computer.png)

- As the number of families earning between $10,000 and $15,000 increases in a given zip code, the number of households with no computers.

![Total_Less_than_$10,000_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_Less_than_10000_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning less than $10,000 increases in a given zip code, the number of households with computers but no internet subscription also tends to increase.

![Total_Less_than_$10,000_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_Less_than_10000_Families_vs_Total_No_Computer.png)

- As the number of families earning less than $10,000 increases in a given zip code, the number of households with no computers.

![Total_$15,000_to_$24,999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_15000_to_24999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning between $15,000 and $25,000 increases in a given zip code, the number of households with computers but no internet subscription also tends to increase.

![Total_$15,000_to_$24,999_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_15000_to_24999_Families_vs_Total_No_Computer.png)

- As the number of families earning between $15,000 and $25,000 increases in a given zip code, the number of households with no computers.

![Total_$25,000_to_$34,999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_25000_to_34999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning between $25,000 and $35,000 increases in a given zip code, the number of households with computers but no internet subscription also tends to increase.

![Total_$25,000_to_$34,999_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_25000_to_34999_Families_vs_Total_No_Computer.png)

- As the number of families earning between $25,000 and $35,000 increases in a given zip code, the number of households with no computers.

![Total_$100,000_to_$149,999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_100000_to_149999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning between $100,000 and $150,000 increases in a given zip code, the number of households with computers but no internet subscription also tends to increase. (smaller increase than the previous ones)

![Total_$100,000_to_$149,999_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_100000_to_149999_Families_vs_Total_No_Computer.png)

- As the number of families earning between $100,000 and $150,000 increases in a given zip code, the number of households with no computers. (much smaller than previous ones)

![Total_$150,000_to_$199,999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_150000_to_199999_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning between $150,000 and $200,000 increases in a given zip code, the number of households with computers but no internet subscription tends to decrease.

![Total_$150,000_to_$199,999_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_150000_to_199999_Families_vs_Total_No_Computer.png)

- As the number of families earning between $150,000 and $200,000 increases in a given zip code, the number of households with no computers tends to decrease.

![Total_$200,000_or_more_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_200000_or_more_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the number of families earning more than $200,000 increases in a given zip code, the number of households with computers but no internet subscription tends to decrease.

![Total_$200,000_or_more_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Total_200000_or_more_Families_vs_Total_No_Computer.png)

- As the number of families earning more than $200,000 increases in a given zip code, the number of households with no computers tends to decrease.

![Mean_income_(dollars)_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Mean_income_(dollars)_Families_vs_Total_No_Computer.png)

- As the mean income of families in a zip code **increases**, the number of households **without a computer** tends to **decrease**
- Families with higher mean income are more likely to afford computers, fewer households in wealthy areas lack basic technology

![Median_income_(dollars)_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Median_income_(dollars)_Families_vs_Total_Has_a_computer_Without_Internet_subscription.png)

- As the mean income of families in a zip code **increases**, the number of households **with a computer** without internet subscription tends to **decrease**
- Families with higher mean income are more likely to afford computers, fewer households in wealthy areas lack basic technology

![Median_income_(dollars)_Families_vs_Total_No_Computer.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/Median_income_(dollars)_Families_vs_Total_No_Computer.png)

- A **decreasing scatterplot** between **median income** and **total no computer** means that areas where **most families have a higher middle income** tend to have fewer families without computers.

Correlation Matrix

![output.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/output.png)

![output(1).png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/output(1).png)

![output(3).png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/output(3).png)

![output(4).png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/output(4).png)

![PCA.png](Digital%20Divide%20WorkBook%205b597e6b613e435997ccb39215163f41/PCA.png)