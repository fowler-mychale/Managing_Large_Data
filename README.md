# Managing_Large_Data


## The Raw Data at a glance.
At a glance. This dataset has 1,584,315 rows and 26 columns. The dataset is also filled with missing values, null/Nan cells, information that is incomplete and consolidated information that should have its own column(s). In its current form. This information is difficult to work with, so adjustments to the datset is necessary.

Data in Raw Form


| DR Number     | Date Reported |Date Occurred| Cool  | Cool  | Cool  | Cool  | Cool  | Cool  |       |        |       |       |
|---------------| :-------------|-------------|-------|-------|-------|-------|-------|-------|-------|--------|-------|-------|
| 1584316       | 12/31/2005    | 12/28/2005  | Cool  | Cool  | Cool  | Cool  | Cool  | Cool  | Cool  | Cool   | Cool  | Cool  |
| 102005556     | 01/25/2010    | 01/22/2010  |       | Cool  | Cool  | Cool  | Cool  | Cool  | Cool  | Cool   | Cool  | Cool  |
| 101822289     | 11/11/2101    | 11/10/2010  |       | Cool  | Cool  | Cool  | Cool  | Cool  | Cool  | Cool   | Cool  | Cool  |

## Adjustments to the document.
Once it was determined what information I could and could not use; I went ahead and removed them from the set. Upon review, I also realized that I could add an entirely new column called "Difference" which is the difference (in days) from the day the crime occrred and reported. I also thought it prudent to seperate the geolaction column into two individual columns for latitude and longitude. The document went from 26 columns to now 14.

After Cleaning the Information
<img src="After.PNG" width="1000" height="250">


## Actionable Information
Now that the data is manageable. We can create insights. In order to create a coherent dashboard. I thought it necessary to limit the information to focus on a single year (2017). 

<img src="Data.PNG" width="1000" height="450">
</br></br>

### Tools used for this project
- Python 3.8.2
- AWS Quicksight
- MS EXCEL

