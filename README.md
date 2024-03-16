
Walmart Business Case Study

Problem Statement
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between gender, Age, marital status, occupation, duration of stays in one city and other factors of the customers.


 Statistical Summary (Analyzing the Basic Metrics)
Total Customer Base: There are a total of 550068 customer details.
Age Diversity: The dataset includes 7 unique age groups. The age group 26-35 has the highest number of transactions, with a total of 219,587. 
Product_ID: In the 550,068 transactions, there are 3,631 different products. The product with the code P00265242 is the top seller, having sold a maximum of 1,880 units.
Gender: Among the 550,068 transactions, 414,259  transactions were made by males. This indicates a significant difference in buying behavior between males and females.
Stay_In_Current_City_Years: Customers who have stayed in the current city for 1 year account for the highest number of transactions, reaching 193,821. 
User_ID: Out of 550,068 transactions, there are 5,891 unique user IDs. 
Marital_Status: Unmarried customers made up 324731 of the total transactions, while married customers accounted for 225337.
Purchase:The amounts people spent on purchases show a big range. The smallest purchase was $12, while the biggest one was as high as $23,961. The middle point, or median purchase, is $8,047, which is less than the average purchase amount of $9,264. This suggests that the majority of purchases are lower in value, but there are a few very expensive purchases that make the average higher. It's like the data is leaning more towards the right side indicating a right-skewed distribution.

#Finding Duplicates and Missing values

There are no duplicate values in the dataset.
There are no missing values in the dataset.

#Non-Graphical Analysis
User_ID - Among 5,50,068 transactions there are 5891 unique user_id, indicating the same customers buying multiple products.
Product_ID - Among 5,50,068 transactions there are 3631 unique products,with the product having the code P00265242 being the highest seller, with a maximum of 1,880 units sold.
Gender - Out of 5,50,068 transactions, 4,14,259 (nearly 75%) were done by male gender indicating a significant disparity in purchase behavior between males and females.
Age - We have 7 unique age groups in the dataset. 26 - 35 Age group has a maximum of 2,19,587 transactions.
Stay_In_Current_City_Years - Customers with 1 year of stay in the current city accounted for a maximum of 1,93,821 transactions among all the other customers.
Marital_Status - 59% of the total transactions were done by Unmarried Customers and 41% by Married Customers.

Outliers Detection



Calculating the IQR:
Q1= 5823.0
Q3= 12054.0
IQR= 6231.0
Upper band= 21400.5
Lower band= -3523.5
Median 8047.0

Observations
There are 2677 outliers in the purchase amount column.
Outliers
0.48% values in the Purchase column are outliers.
Univariate Analysis
Purchase Amount Distribution

Most order values lies in the range of 5000 - 10000
There are more orders in the range 15000 - 16000 followed by 11000 - 11500 range and a few also in the 19000 - 20000 range.
Gender

The data shows a big difference in how
many males and females bought things during Black Friday. About 75.3% of the purchases were made by males, and only 24.7% were made by females.


Marital Status

About 59% were made by unmarried customers compared to married couples, who made up 41% of the purchases.

Distribution of City Category


City B had the most transactions, making up 42% of the total. Following that, City C had 31.1%, and City A had 26.9%.

Product Category Distribution

Categories 5,1 and 8 have significantly outperformed other categories with combined Sales of nearly 75% of the total sales suggesting a strong preference for these products among customers.
The least frequent bought are category 9 followed by 17 and 14.

Age


The largest group of buyers, making up 40%, falls in the age range of 26-35, which is the highest among all age groups.
Buyers in the age groups 0-17 and 55+ are not as common, representing only 3% and 4% of the data, respectively.
It's noticeable that most buyers are between the ages of 18 and 45. Before and after this range, there are fewer buyers.

Occupation

The most common buyers have occupation code 4, with occupation codes 0 and 7 following closely behind. On the other hand, people with occupation code 8 are the least frequent buyers.
Distribution of Customer's stay in current city

Most buyers are in their current cities since 1 year followed by 2 years and 3 years.
Product ID with Maximum sales


The best-selling products in Walmart's Black Friday sales include the item with ID P00265242 leading the way, selling 1,880 units. Following closely are P00025442 with 1,615 units sold and P00110742 with 1,612 units sold.

Bi-variate Analysis
Purchase vs Age

Among different age groups, the age range of 51-55 exhibits the highest average order value, reaching approximately 9534. Conversely, the age group 0-17 has the lowest average order value, around 8933.
The highest order value observed across all age groups is approximately 23960, highlighting the peak spending level. On the other end, the lowest order value, consistent across all groups, is 12.
Purchase vs Occupation


The dataset contains numerous outliers.
The occupation with the highest median value is occupation 17, indicating a concentration of values around a central point. Conversely, occupation 19 has the lowest median value.
Occupation 17 stands out with the highest average order values, reaching 9821, indicating a tendency for higher spending. On the other hand, occupation 9 has the lowest average order value, totaling 8637, pointing to comparatively lower spending patterns in this occupation group.


Purchase vs Gender


Males tend to spend more than females in the observed data. On average, the order value for males is 9437, whereas for females, it is slightly lower at 8734.
Most male purchases cluster around an average order value of 8098, suggesting a common spending pattern. Similarly, for females, the majority of purchases center around an average order value of 7914.

Purchase vs Marital Status

The median value is almost the same between married and unmarried people.
Both types share identical minimum and maximum order values, suggesting uniformity in the range of spending behavior.
The average order value is almost the same between married and unmarried people, indicating a similar overall spending pattern between the two groups.
Purchase vs Product Category




There is a huge difference in the median values for all the product categories.
Among the observed product categories, category 10 stands out with the highest median value, reaching 19197. In contrast, category 19 has the lowest median value, merely 37.
The average order value for category 10 is the highest, totaling 19675, highlighting a propensity for higher spending in this category. Conversely, category 19 has the lowest average order value, also 37, indicating lower overall spending in this particular category.
Category 19 emerges as the least preferred or least frequently bought product category, given its lower median and average order values compared to other categories.

Purchase vs City Category



City Category C takes the lead with the highest median order value, followed by City B and City A. This suggests a central tendency towards higher values in City C compared to the other two.
The mean order value for City C is the highest, followed by City B and City A. This indicates that, on average, transactions in City C tend to have higher values compared to those in City B and City A.










Purchase vs Stay in Current City

Across all the years, there is uniformity in the median values, suggesting stability in the central tendency of order values.
The average order values, falling within the range of 9180 to 9320, remain nearly identical across the observed years, indicating a consistent average spending pattern.
The highest order value remains the same across all the years, suggesting a consistent spending habit regardless of the specific year.





Multivariate Analysis
Purchase vs Gender vs Marital Status vs Stay in the current city

Observations
Across age groups, the median values for females aged 18-25 are notably the lowest, while the medians for other age categories exhibit comparable values. Conversely, the highest median values are consistently observed in the 51-55 age group.
Examining city categories, both females and males exhibit the highest median spending in city category C compared to cities A and B.
Marital status appears to have no discernible impact on spending habits for both genders. However, it is noteworthy that median spending values for males tend to be higher than those for females.
Delving into the duration of stay, female spending patterns reveal slightly lower median values for those residing for 0 and 3 years compared to other durations.




Heat-Map
Purchase vs Occupation vs Product Category 





Observations
The analysis reveals a negative correlation of -0.0076 between Product Category and Occupation, suggesting a potential relationship that merits further investigation.
A positive correlation of 0.021 has been observed between Purchase and Occupation, indicating a mild association between these two variables in the context of the study.
An impactful negative correlation of -0.34 has been identified between Product Category and Purchase, implying a potentially influential connection that merits closer scrutiny in understanding the dynamics between these aspects.








Pairplot
Purchase vs Occupation vs Product Category 








Constructing the Confidence Interval of 95% for sample sizes of [30,300,3000,30000]

As the purchase amount distribution is not Normal. So we will be using the Central Limit Theorem. It states the distribution of sample means will approximate a normal distribution, regardless of the underlying population distribution.


After building the Central Limit Theorem (CLT) curve, we will create a confidence interval predicting population mean at 95% Confidence level. 
We will use three different sample sizes of - [30,300,3000,30000]


Gender vs Purchase



Observations
It indicates that as the sample size increases, confidence intervals become more refined and narrower. In the context of business, this implies that larger sample sizes contribute to more dependable insights and precise estimates.

It is evident that, with the exception of the Sample Size of 30 and 300, confidence intervals do not overlap as the sample size grows. This implies that the average spending per transaction between men and women.

With 95% confidence, the average for spending among males lies within the range of $9,393 to $9,483, and for females, it falls between $8,692 and $8,777.
Men tend to spend more per transaction than women. 

Marital Status vs Purchase




At 95% confident that the true population average for married customers falls between $9,217 and $9,305, and for unmarried customers, it falls between $9,222 and $9,311.

The overlapping confidence intervals of average spending for married and unmarried customers indicate that both married and unmarried customers spend a similar amount per transaction. This implies a resemblance in spending behavior between the two groups.




Age vs Purchase



We can say that age group does not have much effect on the spending of customers as their interval range is overlapping with 95% confidence intervals.

Insights

Confidence Interval by Gender

Male confidence interval of means: (895617.83, 955070.97)
Female confidence interval of means: (673254.77, 750794.02)

Confidence Interval by Marital_Status
Married confidence interval of means: (806668.83, 880384.76)
Unmarried confidence interval of means: (848741.18, 912410.38)

Confidence Interval by Age
For age 26-35 --> confidence interval of means: (945034.42, 1034284.21)
For age 36-45 --> confidence interval of means: (823347.80, 935983.62)
For age 18-25 --> confidence interval of means: (801632.78, 908093.46)
For age 46-50 --> confidence interval of means: (713505.63, 871591.93)
For age 51-55 --> confidence interval of means: (692392.43, 834009.42)
For age 55+ --> confidence interval of means: (476948.26, 602446.23)
For age 0-17 --> confidence interval of means: (527662.46, 710073.17)
























Recommendations
Gender-Specific Recommendations:
Target Male Customer Retention and Acquisition, Recognizing that men spend more than women, the company should prioritize retaining existing male customers and attracting new ones.
Tailored Marketing for Females, Since females generally spend less, the company should develop targeted marketing strategies to address their specific needs and potentially increase their spending.
Product Category Strategy:
Products in categories 1, 5, 8, and 11 show high purchasing frequency, indicating customer preferences. The company should focus on increasing sales of these products and explore strategies to promote less-purchased items.
Focusing on Unmarried Customers:
Unmarried customers exhibit higher spending compared to married customers. The company should concentrate on acquiring and retaining unmarried customers.
Age-Specific Marketing:
Engage Younger Consumers with Incentives (0-17 Years),Customers in the 0-17 age group have the lowest spending per transaction. To attract more young shoppers, the company can offer games and incentives tailored to the preferences of the younger generation, creating a more engaging and enjoyable shopping environment. Implementing special offers and games for the 0-17 age group can attract families and boost sales.
Attract Younger Shoppers with Games(18-25), Introducing games in the mall can attract a younger audience and contribute to increased sales. Management should explore interactive strategies to engage younger customers.
Tailor Offerings (26-45),  Given that the age group 26-45 drives the majority of sales, Walmart should tailor its product selection offering exclusive deals on popular products.
Enhance Shopping Experience for Age Group 51-55, The 51-55 age group exhibits the highest spending per transaction. Walmart can enhance their shopping experience through exclusive pre-sale access, special discounts, and personalized recommendations.
City_Category C Revenue Boost:
Male customers in City_Category C spend more than those in other categories. Increasing product offerings and marketing efforts targeting the males in City_Category C can enhance overall revenue.



















