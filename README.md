# Online-retail

Approaches:-

Step 1 - Viewing and cleaning data being the initials, we started with importing necessary libraries, mounting drive and storing data in variables for deriving meaningful insights. 

Step 2 -  Next step being data analysis and visualization, where we analyzed our data distribution as univariate, bivariate and multivariate plots.

Step 3 - Presence of null values would have created possible errors in the further steps, so we dropped null values. As a part of feature engineering we have changed format of invoice_date and split into day, year, month. We have removed outliers from the dataset

Step 4 - We performed RFM analysis followed by our Last step which was to perform clustering nd unsuperwised algorithms, we applied k-means, elbow method, dendograms using single and complete linkages

![rfm](https://user-images.githubusercontent.com/112775752/211192801-0d135328-186d-48f9-b9ce-3502b6956ad3.png)

Why customer segmentation?
Grouping clients according to their variances in behaviour, demographics, geography, etc., is helpful. Understanding various client groups can help with the following:
Market Research client comprehension optimum product positioning looking for new clients revenue increase.

Conclusion:
There were more number of purchases in the year 2011
It was observed that in the month of January, August, September and December there is surge in total price.
Invoice weekday vs quantity shows that most number of purchases are made on friday(black friday sale) and least on sunday
Most purchases are of paper craft, little birdie category followed by picnic baskets.

Finally, we looked at how we may divide up our consumer base based on the demands of our company. RFM can be applied to all of your clients or just a portion of them. For instance, you might first create client segments based on a region or other demographics, and then create groups based on historical, transaction-based behaviour. RFM analysis may assist in providing answers to many questions about their customers, which can assist businesses in developing marketing plans for their clients, keeping hold of sliding clients, and making recommendations to clients based on their interests. To divide up our consumer base into multiple clusters with a high degree of similarity, we employed the K-means technique. K-means did a good job, in my opinion.
