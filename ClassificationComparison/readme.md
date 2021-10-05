# Classification Algorithm Comparison

Two classification algorithms chosen
1. Decision Tree 
2. KNN

The data set [Link](https://archive.ics.uci.edu/ml/datasets/Census+Income)

After visualizing the "adults.name" and the "adult.data" files, can be able to find there are eight categorical and six continuous attributes.

![N|Solid](./Screenshots/1.DataInformation.png)

No missing values or no such data containing "nan". But a few attributes such as workclass, occupation and native_country have the "?" values. So, these values are replaced with the replacing approach called “Mode”.

No such data found with missing or nan

![N|Solid](./Screenshots/2.NanCheck.png)

"?" found in 
1. workclass

![N|Solid](./Screenshots/3.WorkClass.png)

2. occupation

![N|Solid](./Screenshots/4.Occupation.png)

3. native_country

![N|Solid](./Screenshots/4.Occupation.png)

The replacing approach called `Mode` applied to handle the "?" values.

Some other oberservation were also found, 
1. The number of incomes "<=50K" is around 76% and ">50K" is around 24%. So, the class distribution is moderately imbalanced.

![N|Solid](./Screenshots/5.IncomeProbability.png)

2. There is a significant income difference between people who are working in the 'Private'. Through the graph, we can also see most of the people are from the 'Private' sector.

![N|Solid](./Screenshots/6.WorkClassComparition.png)


3. Male has more probability than Female to earn “>50K” income.

![N|Solid](./Screenshots/5.MaleFemaleComparition.png)


4. From the age distribution, we can see the youngest user is 17years the oldest is
90years.

![N|Solid](./Screenshots/3.WorkClass.png)


5. Average 45 years people are getting “>50K” and 37 years people are getting “<=
50K”

![N|Solid](./Screenshots/7.AgeDistribution.png)


6. There is a gradual decrease in the number of people earning “<=50K” respectively
when their age gets higher.

![N|Solid](./Screenshots/8.AgeWithIncome.png)
