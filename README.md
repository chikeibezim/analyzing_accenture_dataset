# Analyzing Accenture Dataset (Social Buzz)

### Analyzing data based on datasets presented by Accenture.

The Analysis is for a social platform (Social Buzz) looking to learn more about their data and seeking professional help through analysis.

The analysis was carried out using python, and libraries used include Pandas, MatplotLib for visualization and Numpy for several analysis and computations. And analalysis was conducted on over 24,000 reactions made on 1000 posts.

#### Analysis Conducted Inludes Finding:
- The Top Five most popular Categories of Content Posted by Users
- The most popular content
- The most most popular reaction type used by users
- The most commonly used media type
- Also analyzed the monthly engagement rates on contents to find out the top performing months

#### Steps Taken:
- Identified the datasets that will be useful or necessary for our analysis
- Cleaned the datasets by doing the following:
 i. On the Reactions table, removed the rows that contained missing values in the Type column. Since users can post anonymously on the platform, didn’t remove fields with missing values on the User ID column. Also changes the column name Type to Reaction Type to give it a better meaning. Removed unnecessary columns that weren’t needed for our analysis.
ii. On the Content Dataset, removed unnecessary columns, and corrected several errors in the Category column

- Merged the three Datasets
- Grouped the merged dataset by Categories and summed up their scores
- Sorted the result from the last process in descending order and selected the top 5 categories
- Visualized our Findings

#### Findings and Recommendations:
- Although the most popular Category is Animal, all top five categories are also in same percentile range which suggests that several different category groups are doing great as well or related in some sense.

- From the top 5 categories, we can deduce that majority of Social Buzzes user engage more with food related contents and another majority engage with science and technology. This tell us more about the habits or interests of their users and how better they can target their adverts to get and retain more users on their platform

- Engagements on contents have been quite  consistent within the timeframe analyzed.

- With More Contents, we can get more useful insights to share about how Social Buzz can learn more about their users and also perform much better in future
