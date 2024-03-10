# Data Engineering Project - End to End Youtube Data Analysis

Canadians prefer Vlogs & documentaries, Britishers top Entertainment watch time, and Americans lead in Science & Technology videos on Youtube among these three!📺✨

Embarked on an epic journey with this End-to-End Data Engineering project! 
I've delved into AWS, unlocking a secure and streamlined solution for analyzing YouTube data across regions.

🛠 **Services Used**:-
 AWS Glue (Crawlers, Visual ETL jobs, Glue Catalog.), AWS Lambda, Quicksight, S3, Athena, Cloudwatch, IAM, pySpark, Python, Pandas and AWS Quicksight to visualize.


🛠 **Services Used:**
- AWS Glue (Crawlers, Visual ETL jobs, Glue Catalog)
- AWS Lambda, Quicksight, S3, Athena, Cloudwatch, IAM
- pySpark, Python, Pandas
- AWS Quicksight for visualization

🔄 **Project Lifecycle:**

**Data Ingestion**: Built a robust mechanism using AWS S3 bucket for ingesting partitioned data from external source plus internal aws services.

**ETL Operations**: Transformed raw CSV data to parquet after mapping correct schema changes and null validations. Certain region wise data was not encoded but filtered. So data was filtered region wise using predicate pushdown. Parquet is a fast, optimized and efficient hybrid file storage format. Hence, proper format for meaningful analysis. Used: AWS Glue, ETL jobs, Database, Tables and Crawlers to crawl data from S3 bucket.

**Data Lake**: Established a centralized repository to efficiently store data from multiple sources and services. Stored raw, cleaned and transformed data using AWS S3 and Glue Catalog. 

**Data Pre-processing**: Unstructured to Structured Data conversion. The raw json data was flattened and filtered on AWS Lambda function using python, pandas and aws wrangler libraries to perform the read, write and store the normalized json data in new cleaned S3 bucket in parquet format. A trigger was created to automate execution of lambda function on data load in raw S3.

**Analytics**: Constructed an insightful dashboard to analyze data and get key findings and answers. Used: AWS Athena for querying data and creating new analytics database. AWS Quicksight - For dashboarding and BI service (offers cloud-based analytics).


**Personal Key Takeaways were** - 
AWS Concepts 
Full Data engineering lifecycle workflow.
Troubleshooting and error resolution. Pleased to tackle and solve various errors which not only helped me to understand AWS in more depth but also made me explore more options and alternatives.

**Data source** - https://www.kaggle.com/datasets/datasnaek/youtube-new
