# About Boomerangs Incorporated project
Boomerangs Incorporated sells gel boomerangs in different sites like amazon, ebay etc,. The main task of the this project is to build revenue reports and interactive dashboards using excel and power BI. so, I have taken their sales data and created different reports and dashboards for client.

# Steps Involved

•	Extracted the Big Data from Amazon’s SQL server database and transformed using power query

•	Loaded the data into columnar database and compressed 7.7 million rows of data into 25 megabytes

•	Calculated columns and tables are created for building a star schema and hidden ineffective columns

•	Created explicit DAX measures to use it in Data Model Pivot tables and charts

•	Imported Data Models of Excel into Power BI desktop and created interactive reports and visualizations

•	Published both the Excel and Power BI reports to powerbi.com and pinned the dashboards live


# Reports created in this project 
	▪ Total revenue by year, product and country
	▪ Total COGS 
	▪ Total gross profit 
	▪ Gross profit percentage 
	▪ Running total 
	▪ Average daily rev 
	
# Dash Boards 
	▪ Revenue reports 
	▪ Gross profit analysis by product, year and country
	▪ Units analysis by year, month and product

# Formulas used in this project

  	▪ Total revenue = sum(line revenue) (or) sumx(each product * retail price) - revenue discount
	▪ Total cogs = standard cost* quantity * net standard cost
	▪ Total gross profit = total rev - total cogs
	▪ Gross profit % = Total gross profit / total rev
	▪ Running total = cummulative toatal (adds each days total )
  	▪ Average daily rev = toatal revenue of that month/30 days


# Here are links to dashboards:
[Reports](https://app.powerbi.com/groups/7aea0391-541a-4b86-97ec-dac690eb0521/dashboards/f338ceda-dbc8-4c6c-b9a7-98acc37fe3b9?ctid=ee327874-4c53-4afc-b9ff-7eff8190191a)

[Gross profit and Units analysis](https://app.powerbi.com/groups/7aea0391-541a-4b86-97ec-dac690eb0521/dashboards/10344176-46e1-4a70-8c59-d9dd75a2b741?ctid=ee327874-4c53-4afc-b9ff-7eff8190191a)
