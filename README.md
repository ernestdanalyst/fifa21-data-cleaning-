# fifa21-data-cleaning-
![image](https://user-images.githubusercontent.com/128243939/228189788-425cad47-6fa2-4389-b69d-a3dda26c0b03.png)
A dirty data makes a dirty analysis , so take a walk with me

# Introduction

This is a rundown of the cleaning process for FIFA '21 dataset. This data set was provided as part of a challenge #Datacleaningchallenge launched on twitter by data ethusiasts to test the prowess of newbies , intermediate and pro Data analyst alike for a large messy dataset.

The data set contains 18,979 rows and 77 columns of football players statistics and demography in 2021 The dataset is publicly available on kaggle which contains data scrapped from sofifa The datafile also includes a Data dictionary as well as a column named player url which contains a link to the player profile on sofifa to give the analyst furher insight and full details of the player in view in case of missing information.

My prefered tool for this Data cleaning challenge based on proficiency is Power Query as available on Power BI.

# Data Cleaning Process

![image](https://user-images.githubusercontent.com/128243939/228190392-ab2cec7d-c687-443c-9b94-3b95aee56870.png)

To ensure data quality , the following approach was used after loading the data , whitespaces were removed by unticking the button from the viewtab

<h1 align="center">Whitespaces</h1>

| Before | After |
|--------|-------|
![image](https://user-images.githubusercontent.com/99989624/224610838-f6b78c4b-b204-42d9-b158-f7aeacb6cda8.png) | ![image](https://user-images.githubusercontent.com/99989624/224610689-763b528d-9eed-431a-8b7d-2d5a54abaa32.png)

**1. Data Auditing** : To ensure data quality, during the auditing stage of understanding the data and identifying any inconsistencies, missing values, or errors that need to be addressed, the following columns were marked for cleaning ; Name, Longname , Age , OVA , POT , Club , Contract , Positions , Height , Weight , Best position , Joined , Loan End date , Value, wage , release clause , W/F , SM , IR , and Hits.







