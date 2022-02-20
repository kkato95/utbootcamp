# An Analysis of Kickstarter Campaigns
## Running anaysis on the successful and failed donations and observed the distribution using median and IQR
We analyzed the success of donation campaigns to various types of entertainment. In particular, we observed the goal amount compared to the pledge amount. Our analysis focused on Parent Category, theatre. We created new columns below to analyze data:
  1. Percentage Funded - What percent of the goal was reached? (Over 100%, then goal was reached)
  2. Average Donation - "pledged"/"backers_count"; Using "IFERROR" was able to place a 0 in place of an error messages for values/0
  3. "Year Created Version" and "Date Ended Version" - short date for when the donation period began and ended
  
  Analysis of Donations Data:
  1. Category Statistics - "theatre" only pivot table analysis
    - Lists out the number of cancled, failed, live, and successful donation campaigns for the theatre category
    - Pivot table graph: ![Parent Category Outcomes stacked_bar](https://user-images.githubusercontent.com/99375741/154866356-b7b665ee-7562-4438-8750-9b289afccd0f.png)

  2. SubCategory Statistics - "theatre" -> "plays" only
    - Lists out the number of cancled, failed, live, and successful donation campaigns for the theatre category and plays subcategory
    - ![Subcategory Statistics graph](https://user-images.githubusercontent.com/99375741/154866419-0def8109-572a-4a8c-9ddb-bf9ae5cecdaa.png)
 
  3. Outcomes Based on Launch Date
    - Pivot table line graph: ![Outcomes based on Date](https://user-images.githubusercontent.com/99375741/154866528-a6297327-e889-4940-b95a-cb89937440e4.png)
