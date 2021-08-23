# Kickstarter Challenge

## The purpose of this project is to explore how fundraising campaigns in the Kickstarter dataset fared based on the following two factors; 
1.	their launch date, particularly the launch months and 
2.	funding goals. 

## Analysis and Challenges

### The following analyses were performed to visualize how campaign outcomes (“successful”, “failed”, “canceled”) feared bases on launch date,:
- A pivot table analysis was performed in excel to show the similarities between the dates that campaigns were created and campaign outcomes, i.e., “successful”, “failed” and “canceled”. 

- Specifically, the following operations were performed in the pivotable field in excel to generate the pivot table:

1.	“date created conversion” was dragged to the “Rows” field and “outcomes” was dragged to the “Value” field. 

2.	Data in two different columns, “Parent Category” and “Year” were used as filters in order to make the data more specific for the purpose of this project. 

-	The parent category data point was filtered to select only “theater” campaigns- Louise’s interest. 

-	The “Year” datapoint was filtered to allow all the years in the dataset to be included in the analysis. The “Year” data point was created from the “Date Created” columns to   extract the exact year that each campaign was created using the Year ( ) function in Excel.

3.	“live” campaigns, i.e., campaigns that are still running, were excluded from this analysis because we cannot determine at the time of analysis whether these campaigns will succeed, fail or be canceled. This exclusion was performed by filtering the goal outcomes in the “column label” of the pivot table to only include “successful”, “failed” and “canceled” outcomes. 

-	After the pivot table was generated, a line chart was generated using the datapoints in the pivot table. The line chart helps to visualize how campaign outcomes (“successful”, “failed”, “canceled”) feared bases on launch date. See line chart titled "Outcome Based on Launch Date" in the attached Resources folder.

### No challenges were encountered in this analysis, however, one challenges that could be encountered is if data for all campaign categories were used instead of using the “Plays” subcategory data (Louise’s subcategory of interest). Using insights from analysis for all categories will bias the findings and hence, negatively affect Louise’s decisions.

### The following analyses were performed to visualize outcome based funding goals amount:
-	First, outcome goal amounts were grouped into twelve different ranges, “Less than 1000”, “1000 to 4999”, “5000 to 9999”, “10000 to 14999”, “15000 to 19999”, “20000 to 24999”, “25000 to 29999”, “30000 to 34999”, “35000 to 39999”, “40000 to 44999”, “45000 to 49999”, and “Greater than 50000).

-	The “COUNTIFS( ) function was used in excel to count the numbers of outcome goals (“successful”, “failed”, “canceled”) based on their respective goal amount category, as stated above. This excel operation generated a data table consisting of numbers of successful, failed and canceled outcomes in twelve different goal amount categories. These datapoints were further summed up along the rows to calculate the total number of campaigns for each goal amount category.
  
-	These datapoints were converted into percentages. For example, the number of successful campaigns “less than 1000” is 141 and the total number of all campaigns less than 1000 is 186. Therefore, the percentage of successful campaigns less than 1000 was calculated as 141/186 equals 76%. The rest of the table was populated using this formula.

-	Further, the data in this table (above) was used to generate a line chart to visualize the percentage of successful, failed, canceled plays bases funding goals amount. See line chart titled "Outcome Based on Goal" in the attached Resources folder.

### I encountered the following challenge while I was trying to generate a line chart from the datapoints in the table:
- The chart included all the datapoints in the which makes the graph unreadable. However, I was able to resolve this issue when I referred to the notes I took from last Wednesday’s virtual class. Specifically, I clicked on the chart and a filter icon emerges. I clicked on the filter icon and it gave me the option to select the datapoints I want to be displayed in the chart. With this, I was able to resolve the issue and the line chart came out exactly the way I wanted to.

## Results

-	Below are the conclusions drawn from the Theater Outcomes Based on Launch Date analysis (See line chart titled "Outcome Based on Launch Date" in the resources folder):
1.	There are more successful campaigns than failed and canceled campaigns. This indicates that the kickstarter fundraising platform is effective. 
2.	Campaigns launched in May, June, and July tend to be more successful than those launched in other months of the year. This result indicates that Louise have higher chances of launching successful campaigns during these months, May, June and July.

-	Below is the main conclusion drawn from the Outcomes based on Goals analysis (See line chart titled "Outcome Based on Goals" in the resources folder):
 - Campaign goal amount within the range of 1000 to 4999 have higher chances to be successful (76% and 73%, respectively) than those that are higher goals. Also, the analysis shows that campaign goal amounts within Louise’s goal range (10000) have 45% chance to be successful. This indicate that Louise’s campaign goal have a higher chance to be successful if the goal is reduced to the range of 1000 and 4999.  

- Followings are some limitations of the dataset that can also affect the application of insights drawn from above analyses:

1.	First, while the dataset provides rich insights into how fundraising campaigns feared on the kickstarter platform from 2009 to 2017, it is important to note that current and future campaigns could feared differently due to shifts in environmental factors, such as economic, political and cultural situations.

2.	Second, outlier analysis conducted to identify any unusually different data points in the dataset confirmed that such data points are present. For example, the outlier analysis identified two successful campaigns goals that are greater than 50000. This indicates that findings for successful campaigns are likely to be influenced by these the two huge campaign goals. I recommend for Louise to consider this while deciding whether to completely rely on above conclusions or not.

-	A pivot table showing the association of “country” and campaign outcomes could be created to further gain insights from the Kickstarter data. This will allow us to know whether campaign outcomes are driven by location, i.e., country. If this assumption is supported, Louise could use such information to create her campaign at a location where the campaign will have a higher likelihood to be successful.  


# Kickstarter-analysis
## Analysis of kickstart data to uncover trends
### To determine specific factors that make project campaigns successful
## Analysis and Challenges
### Analysis of campaign outcomes based on Launch Date
![Outcome Based on Launch Date](https://user-images.githubusercontent.com/88128466/129490353-ffe38752-5a1b-4f2d-9dd6-6f6eeb07730c.png)
### Analysis of outcomes based on Campaign Categories
![Outcome Based on Campaign Categories](https://user-images.githubusercontent.com/88128466/129490429-46450332-34a8-4121-831f-0e905af82f00.png)
### Analysis of outcomes based on Theater Subcategories
![Outcome Based on Theater Categories](https://user-images.githubusercontent.com/88128466/129490455-0365fc03-e093-4804-8db9-91269cad56de.png)
### Analysis of Descriptive Statistics of Successful and Failed Campaigns
![Descriptive Statistics](https://user-images.githubusercontent.com/88128466/129490481-f1af891c-3b5d-48e6-9155-3ed552ab2122.png)
### Analysis of five Edinburgh Festival Plays
![Descriptive Statistics](https://user-images.githubusercontent.com/88128466/129490700-d159ada2-04a7-4f3b-8d29-be3a151bde5b.png)
Challenges encountered Outliers
![Outlier Analysis Chart](https://user-images.githubusercontent.com/88128466/129490726-0dad6648-0b37-4fd2-bd28-08bdd8cc7bde.PNG)
## Results
### February, May, and June are the top three months for successful campaigns
### January, July and October are the top three months for failed campaigns
### Theater campaigns are the most campaigns, followed by Music and film categories
### In the Theater Category, Plays are the most successful campaigns having huge margin over Musicals and Spaces
### Descriptive Statistics results show that failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Also, Louise Kickstarter goal is more than twice the average successful Kickstarter goal, so this doesn't look good. 
### Results from measure of Spread analysis shows that some large values, i.e., outliers are driving all of these distributions 


