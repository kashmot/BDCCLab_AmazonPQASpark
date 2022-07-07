# BDCCLab_AmazonPQASpark
BDCC Lab Project with Mark Acot (Term 4 SLT)

Executive Summary

This study focuses on finding interesting insights in the questions and answers in Amazon’s database covering 100 product categories. The authors performed exploratory data analysis using PySpark in AWS EMR to process 19.4 GB of JSON data and discern what are the most common questions that customers ask. The top 3 categories that have the most number of questions are unlocked_cell_phones, basic_cases, earbud_headphones, which is not surprising because these are fast moving goods/expensive items that need customer discernment. The top 3 brands that had the most number of questions are Amazon, Samsung, and Asus, which are all technological companies, that are driving the way we consume technology today.

The methodology is straightforward. After making an EMR cluster and notebook in AWS, the JSON data was parsed and descriptive statistics were performed. Processing the data was done using the Pyspark cluster in the EMR notebook, hence the output display is different from what we are used to when using using Jojie. Installing Pandas, Matplotlib and other necessary directories required working with a lower version that was compatible with EMR's pyspark kernel.

The data is also limited because it only contains text information on the question and answer and no fields on the star rating, time, or geolocation. The database was not augmented and analysis was focused on the data that was available on this dataset.

