# PROFIT ANALYSIS ON 50 STARTUPS
# DATA ANALSYSIS PROJECT 

## ABOUT THE DATASET


### This dataset holds data from 50 startups in New York, California, and Florida. The features in this dataset are R&D spending, Administration Spending, Marketing Spending, location features, and Profit

## DATA SET INFORMATION:

### R&D spending: The amount which startups are spending on Research and development. Datatype: Numerical
- Administration spending: The amount which startups are spending on the admin panel. Datatype: Numerical
- Marketing spending: The amount which startups are spending on marketing strategies. Datatype: Numerical
- State: To which state that particular startup belongs. Datatype: Categorical(Nominal)
- Profit: How much profit that particular startup is making. Datatype: Numerical
- Transformation
1. Creating another column specifying startup no. from 1 to 50

### DATA CONNECTION

![1](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/73748e5e-467b-4afc-b6a2-4ad4d8d984bf)

- Connected to SQL server -18.136.157.135, with the given username and password,
- Query ran to see the table data
- USE project_profit_analysis; (To select the database)
- SELECT * FROM startup; (To select all columns and data in startup table)
- By left clicking on the table ‘startup’ -selected option Table export wizard, selecting all columns and
- selected a local directory to export the csv data.

## DASHBOARD ON POWERBI 

### EXPECTED CHART REQUIREMENTS FOR DASHBOARD

![9](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/a0e7d361-5060-49e5-b88c-c3f3dbc8fdab)

- Top 5 startups with high profit (BAR CHART)
- Last 5 startups with least profit  (BAR CHART)
- Total expenditure by total profited generated (DONUT CHART)
 - Sum of Administration, Marketing, R&D Spend by Specific startup (STACKED COLUMN CHART)
- Total expenditure by total profited generated for each startup (LINE CHART)
- FILTERS :   State , Startup No.

### MAKING PAGES; HOME & DETAIL ANALYSIS
![13](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/e89c7068-e70f-40ea-84b9-23ff1050d1a0)

- In the detail analysis page, creating line chart between Total expenditure, R&D Expenditure, Administration Expenditure, Marketing expenditure and Profit .To know relationship between each of the categories producing profit.
- Used Profit/Expenditure ratio as one of the KPI on this page and created a bar chart between startup no’s and profit /expenditure ratio . To see which startup is producing max profit compared to its investment

![11](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/658488ff-8adb-4834-b1db-f1cc481355d8)

![10](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/3512dc71-24d6-4768-986e-db2c221aba56)


### INSIGHTS FROM DASHBOARD


- The top 6 profitable startups have spent maximum expenditure compared to 50 startups and even in that total expenditure the majority they have spent is on marketing followed by R & D, followed by Administration.
- In general terms the least profitable startups have spent lowest expenditure and with varying distribution in all the three categories, spending almost nil in marketing. These startups expenditure was done majorly in only administration  
- Looking at the linear relationship through line charts. Except for few rare cases total expenditure is directly changing to profit generated. As expenditure increase so does profit.
- Overall looking at the line chart it can be concluded that the profit varies linearly either because of R & D spent or because of amount spent on marketing (the graph is varying similar like total expenditure).
- The amount spent on Administration is almost in same range for all 50 startups making it least factor affecting profit generated.


### CONFIRMATION THROUGH CORRELATION FACTOR

![12](https://github.com/shivakumar313/profit_analysis_50-Startups/assets/137754963/e2c1f1fa-4e23-4acb-936a-0491cd0889de)
- With correlation factor of R&D_spend to profit- 0.97, Marketing to Profit-0.75 and least Administration to profit -0.2.



### SUGGESTION FROM MY SIDE TO COMPANY 

- The major features out of the three-expenditure affecting Profit are Expenditure on Marketing and R&D Expenditure. So, startups should primarily focus on their Marketing and R&D. And managing their Administration expenditure to their sufficient requirement only, until and unless it’s a startup with their primary factor of producing profit from their administration only (services providing company through working staff).






