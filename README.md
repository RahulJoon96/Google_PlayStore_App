# Google_PlayStore_App  [Project Link](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/391929095643206/812076261271208/8761874237841481/latest.html)

About the project:
We have google playstore dataset, present in the DBFS of databricks, containing information of different apps installed such as rating, versions and other details.
 
Agenda -
We need to find out the answers of below mentioned questions in the tabular and graphical format. 
Questions - 
1. 5 top apps based on reviews
2. Top 5 installed apps
3. Apps grouped by free and paid along with installs
4. Categorywise number of apps and their total installation
5. Top 20 paid apps

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

From the DBFS system, we will read the provided dataset csv file in pyspark and will create a dataframe. After cleaning the data in pyspark and creating it in a table format, We will execute sql queries to get the required dataset and will try to find out the answers with the help of tables and graphs.

