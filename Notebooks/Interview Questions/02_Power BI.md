1. Tell me about your self
	1. I completed [Btech] in [cse] specilaization and got opprtunity to work as fresher in [abc] company. I got onboard/Induction training on skills SQL and PowerBI.
	2. From last 3 years iam working as a power Bi developer.
	3. In current Project iam working in IC role. As part of this role i will be speaking directly with Product Owner and getting user stories in jira board. We are following 4 standard user stories 1) Requirment Gathering 2) Development 3) Testing 4) Deployment
- In current Project Iam working with Pobwer BI and SQl are main skills.
- In Power BI the building blocks which iam working are power Query, Power Pivot, Power View, and Power BI Pro and Premium license
	
3. **What are the important components of Power BI?**

   Important components of Power BI are: 
    1. Power BI Desktop
        1. Power Query Editor
        2. Power Pivot
        3. Power View
    2. Power BI Service
    3. Power BI Mobile
2. **What you know about Data Analysis Expressions (DAX)**

    Data Analysis Expressions (DAX) is a library of functions and operators that can be combined to build formulas and expressions in

        Power BI Desktop
        Azure Analysis Services
        SQL Server Analysis Services
        Power Pivot in Excel data models.

    DAX formulas include functions, operators, and values to perform advanced calculations and queries on data in related tables and columns in tabular data models    
3. **Data types of DAX?**
    1. Whole Number
    2. Decimal Number
    3. Boolean
    4. Text
    5. Date
    6. Currency
    refer more details [here](https://docs.microsoft.com/en-us/dax/dax-overview#data-types)
4. **Name two types of connectivity modes in Power BI?**
      1. Import
      2. Direct Query
5. Explain DAX Function Crossfilter
	1. [Read it](https://docs.microsoft.com/en-us/dax/crossfilter-function#:~:text=There%20are%20two%20ways%20to,work%20for%20just%20this%20measure.)
6. How to keep images in Slicer? and filter visulizations based on image selection?
7. How to show negative Values in pie chart?
8. What is HASONEVALUE DAX formula ? Develop Some report?

	https://docs.microsoft.com/en-us/dax/hasonevalue-function-dax

9. How to use **selectedvalue**

	https://docs.microsoft.com/en-us/dax/selectedvalue-function
10. what is ALL dax formula?
11. How to use particulat direction in one mesure calculation?
12. How to implement RLS?
13. How to use Mesure in slicer?

14. How to pass multiple values of disconnected table to visulization?

15. Difference between sum vs sumx in dax.

    https://radacad.com/sum-vs-sumx-what-is-the-difference-of-the-two-dax-functions-in-power-bi

16. common table expression in sql server example
17. Create table from view in sql server?

18. What is query folding in power bi

	https://docs.microsoft.com/en-us/power-query/power-query-folding
19. How to add images ?

	https://www.blue-granite.com/blog/simple-steps-to-embed-images-in-power-bi

    
20. Count Vs CountA 
21. Rolling Months

	https://stackoverflow.com/questions/49146565/show-last-3-months-from-selected-month-in-power-bi

	https://www.youtube.com/watch?v=duMSovyosXE

22. Number of unique rows – by multiple columns

	https://exceltown.com/en/tutorials/power-bi/powerbi-com-and-power-bi-desktop/dax-query-language-for-power-bi-and-power-pivot/number-of-unique-rows-by-multiple-columns/
	
23. Can you  do sub totals in table visulization?

	https://docs.microsoft.com/en-us/power-bi/visuals/desktop-matrix-visual#subtotals-and-grand-totals-with-matrix-visuals

24. What is stepped-layout-with-matrix-visuals
	
	https://docs.microsoft.com/en-us/power-bi/visuals/desktop-matrix-visual#stepped-layout-with-matrix-visuals
	
25.How Many Built-in Joins available in Power BI?

	1. Inner Join
	2. Left Outer Join
	3. Right Outer Join
	4. Full Outer Join
	5. Left Anti Join
	6. Right Anti Join
26. Seeall these 

	https://data-flair.training/blogs/power-bi-interview-questions/

	https://data-flair.training/blogs/power-bi-interview-questions-and-answers/
27. Think and develop below reports.
	![image](https://user-images.githubusercontent.com/20516321/115226802-44837c00-a12d-11eb-94d3-b1ced898ddf1.png)
	![image](https://user-images.githubusercontent.com/20516321/115226863-57964c00-a12d-11eb-8d66-f248102aa75a.png)



28. Think and develop below reports.
	![image](https://user-images.githubusercontent.com/20516321/115226962-785ea180-a12d-11eb-991c-623b1c43dccd.png)
	![image](https://user-images.githubusercontent.com/20516321/115227020-8ca29e80-a12d-11eb-83e2-ca85877e5bca.png)


29. Do you know Power BI Rest API?
30. Do you know power Shell commands of Power BI?
	- https://docs.microsoft.com/en-us/powershell/power-bi/overview?view=powerbi-ps
	- Right click on  Windows power shell ISE > Run as Administartor 
	- Install all below moduls
		```
		Install-Module -Name MicrosoftPowerBIMgmt
		Install-Module -Name MicrosoftPowerBIMgmt.Admin
		Install-Module -Name MicrosoftPowerBIMgmt.Capacities
		Install-Module -Name MicrosoftPowerBIMgmt.Data
		Install-Module -Name MicrosoftPowerBIMgmt.Profile
		Install-Module -Name MicrosoftPowerBIMgmt.Reports
		Install-Module -Name MicrosoftPowerBIMgmt.Workspaces
		```
	- In Power Shell > Click on **New Script** > copy paste below code and change path accordingly.
		```
		Connect-PowerBIServiceAccount
		Get-PowerBIWorkspace | Export-Csv -Path C:\work\powerbi-powershell\ws.csv
		Disconnect-PowerBIServiceAccount
		```
	Click on Run > observe Csv file output
31. Project Methodology (Agil)
32. Errors rectifing (debugging)
33. What is the definition of L1, L2, L3, L4 support levels in IT Operations Management?
	- https://myfirstsite99.wordpress.com/what-is-the-definition-of-l1-l2-l3-l4-support-levels-in-it-operations-management/
34. Write Sql Query to get running totals.
	```sql
	select empno,sal,
	sum(sal)over (order by empno) 
	from emp
	order by empno
	```
35. Difference between summarize and summarizecolumns
	- https://www.sqlbi.com/articles/introducing-summarizecolumns/#:~:text=Another%20difference%20between%20SUMMARIZE%20and,only%20and%20no%20row%20context.
36. Explain about data alerts ?
- https://docs.microsoft.com/en-us/power-bi/create-reports/service-set-data-alerts
37. How many types of gateways are available in power BI?
    1. Personal Gateway
    2. Enterprise gateway
38. When we need to gateway?
    1. For on permise data sources(for example Oracle,Sql Server ,MySql,Excel, Notepad ...etc)
39. What are the ticketing tools available ?
    1. Ivanti
    2. Zendesk
    3. Freshservice ....etc
40. What is GetData in PowerBI ?
    1. GetData is a simple icon on PowerBI used to import data from the source.
41. List out some drawbacks/limitations of using PowerBI ?
    1. PowerBi Doesn't accepts file sizes larger than 1GB and doesn't mix imported data accessed from real-time connections.
    2. There are very few data soures that allow real-time connections to PowerBi reports and dashboards.
    3. it only shares dashboards and reports with users logged in with the same email address.
    4. Dashboard doesn't accept or pass user,account,or other entity parameters.
42. Name some commonly used tasks in the query editor ?
    1. Connect to data
    2. Shape and Combine data
    3. Group rows
    4. Pivot columns 
    5. Create custom columns 
    6. Query formulas
43. How many types of buildings blocks in power BI ?
    There are Five Types of Building Blocks
    1. Visualizations
    2. Datasets
    3. Reports
    4. Dashboards
    5. Tiles
44. What is Visualizations ?
    * Visualization is the visual representation of data in the form of maps, charts, or tables.
45. What is Datasets ?
    * Dataset is a collection of data gathered from various sources like SQL Server, Azure, Text, Oracle, XML, JSON, and many more. With the GetData feature in Power         BI, we can easily fetch data from any data source.
46. What is Report ?
    * Reports are a structured representation of datasets that consists of multiple pages. Reports help to extract important information and insights from datasets to       take major business decisions.
47. What is Dashboard ?
     * A dashboard is a single-page representation of reports made of various datasets. Each element is termed a tile. 
48. What is Tile ?
     * Tiles are single-block containing visualizations of a report. Tiles help to differentiate each report 
49. Name any 3 most useful aggregation functions DAX?
      DAX has a number of aggregation functions, including the following commonly used functions:
        * SUM
        * AVERAGE
        * MIN
        * MAX
        * SUMX (and other X functions)

50. Name any 3 most useful text functions in DAX?
    The text functions in DAX include the following:
       * CONCATENTATE
       * REPLACE
       * SEARCH
       * UPPER
       * FIXED

51. How to Connect Oracle Database from PowerBI ?
    1.Host:PortNumber/SID
52. What can you do within the PowerBI Desktop Query Settings Pane?
    1.Rename a Query step
    2.Delete a Query step
    3.Delete from one Query step to the end
    4.Reorder the steps
53. When you are creating a formula in the Power Query Editor, what does IntelliSense provide a list of ?
    1.Columns
    2.Tables
    3.Functions
54. Which data type can be uploaded directly to PowerBI.com?
    1.Excel Files
    2.Comma-Seperated Value (CSV) Files
    3.PowerBI Desktop Files
55. In the Power Query Editor, you have selected multiple columns. How do you set them all to the whole number data type ?
    Click Data Type Any and Select the Whole Number
56. 
     
       





	






  
    
