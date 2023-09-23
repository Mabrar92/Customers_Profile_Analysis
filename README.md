## Data Analysis of Customer Buying Habits at CardioGood Fitness
As a marketing enthusiast and a data analyst, I take on this [dataset](
<https://www.kaggle.com/datasets/saurav9786/cardiogoodfitness>) with an
interesting scenario of CardioGood Fitness company that is looking to enhance their
marketing strategy by understanding how their potential customer look
like in terms of demographics (customer profiles) for each of their
treadmill product line.

I imported the dataset from Kaggle into SPSS. While cleaning the data I
found no missing and duplicate values. For outliers, I utilized IQR
(Interquartile Range) and Z-Score methods to identify outliers for our
income and miles numerical variables. For income, no outliers were
found. However, for Miles, I found several values above the set
threshold for a Z-score of 3.2. On this criterion, I eliminated several
outliers from the original dataset.

**The Question**

1.  What are the different customer profiles for each Fitness treadmill
    product (TM195, TM498, TM798), considering factors such as age,
    gender, education, and relationship status?

## <u>Data Analysis</u>

Here I present key findings that are not only essential for customer
profile but also answer deeper questions about customers and product
line.

First, let’s find out which product is the people’s favorite. The sales
of TM195 contribute 45.2% to the total sales of the product lines and
is taken home by most customers.

![image](https://github.com/Mabrar92/Customers_Profile_Analysis/assets/18236632/6144d94b-44d6-4901-bb6c-e9e212b245e3)




As gender exhibits different buying habits and behaviors, it is crucial to know the preferred product of each gender.
The male is the dominant gender however, both genders are equally interested
in **TM195** and **TM498**. While **TM798** seems to be a heavy-duty
treadmill which is only popular among males.



![image](https://github.com/Mabrar92/Customers_Profile_Analysis/assets/18236632/0340c8fb-4183-4b92-8ea6-490a4b3fb052)


Age is just a number, right? For marketers, age is an important metric,
and the analysis shows that the median age for all customers is 26,
while the mean age is 28.8. This shows that the age distribution is not normal but skewed to the
right.

![image](https://github.com/Mabrar92/Customers_Profile_Analysis/assets/18236632/526e2855-ace5-4e31-b138-1ea3480b6c79)


Consequently, the typical customer's age falls in the range of 26
to 29 years. Now when it comes to the intent of buying a particular treadmill product, 
the customers planned usage in average no of times per week vs their expected distance coverage in miles reveals an interesting buying pattern.


![image](https://github.com/Mabrar92/Customers_Profile_Analysis/assets/18236632/421aa198-a727-4888-aa09-aa7806bca900)


This suggests that **TM798** is particularly appealing to individuals
with a high-frequency exercise regimen, possibly due to its advanced
features, capabilities, or suitability for intense workouts. The chart
also reveals that **TM798** accounts for the highest number of average
miles as compared to other products. An important insight for the
the marketing team is that individuals who plan to use treadmills 4-5 times
a week expect to cover the largest miles as opposed to the perception
that people with the highest usage group of 6-7 would also achieve more
miles.

The self-claimed fitness levels of customers can give an indication of
how the product use varies among different fitness levels. More than
half of the total customers (55 %) people have a self-proclaimed fitness
level of 3, their go-to product is TM195.

![image](https://github.com/Mabrar92/Customers_Profile_Analysis/assets/18236632/ad8e306d-5d87-478d-a8d0-a092a7552c1a)


Customers with increasing self-claimed fitness levels are directly
correlated with the use of TM798 as their go-to product. This suggests
that the TM798 model may be favored by people who are more
fitness-conscious or already in good shape, possibly because it offers
features and capabilities that align with their fitness goals and
requirements.

## <u>Customer Profile</u>

In this section, I provide customers’ profiles for each product along
with **actionable insights** and **recommendations** to the marketing
team.


  | Product | Age (Years) | Gender | Avg Years of Education | Marital Status | Usage Days/Week | Fitness Level | Avg Income | Avg Miles |
| ------- | ----------- | ------ | ---------------------- | --------------- | --------------- | ------------ | ---------- | --------- |
| TM195   | 26 - 29     | M / F  | 15                     | Single / Partnered | 1-3           | 1-3 / 5      | $46,600    | 80        |
| TM498   | 26 - 29     | M / F  | 15                     | Single / Partnered | 1-3           | 1-3 / 5      | $49,500    | 80        |
| TM798   | 26 - 29     | M      | 17                     | Single / Partnered | 4+            | 4-5 / 5      | $74,700    | 150       |


Customers of the TM195 and TM498 treadmill models, typically aged 26 to 29, with mixed gender, moderate education, and an average income of around $46,600, favor using their treadmills 1-3 days a week, covering an average of 80 miles, and maintaining a fitness level of 1-3, while the TM798 model attracts predominantly male customers of the same age range with higher education and income, who use their treadmill 4 or more days a week, run an impressive 150 miles on average and rate their fitness level at 4-5.


## <u>Recommendations</u>

**For Content Marketing Team**

1.  Highlight the unique features and benefits of the TM195 and TM498 models for the mixed-gender, moderately educated, 26 to 29-year-old audience, emphasizing **affordability** and **ease of use**.

2.  Provide beginner-friendly tips for TM195 and TM498 customers looking to improve their fitness levels gradually, while offering more advanced workout plans and challenges for fitness enthusiasts using the TM798 model.
  
3.  Present success stories and testimonials from customers who align with each treadmill model's profile, these resonate with potential customers who identify with similar demographics and fitness goals, building trust and credibility.


## <u>Conclusion</u>
In this data analysis project, I explored customer data of CardioGood Fitness Company and discovered trends in the buying behavior and characteristics of customers. I then translated my data analysis results into explicit customer profiles for each product and presented key actionable insights for the content marketing team of the company. The marketing team can utilize this knowledge and craft highly targeted strategies, tailored content, and personalized experiences to engage customers effectively and improve their content strategy ultimately contributing to the company's success.


## Please feel free to explore my complete [project portfolio](https://github.com/Mabrar92) to see my data analysis skills in action.
