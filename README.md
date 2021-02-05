Analysis of prices of products found on Walmart.com between Q4 2019 and Q1 2020. 

Team Members: Gary Grisham, Jessica Mendoza, Maria Smith, and Kristin Usry 

The challenges of project two were to include a Python Flask-powered API, HTML/CSS, JavaScript, and at least one database.  The project needed to include a dashboard page with multiple charts that update from the same data.  Our project also needed to include at least one JS library we did not cover in class.  Our data set had to include more than 100 records, have some level of user interaction and include at least three views.  

We chose two data sources from Kaggle.com that represented price points for products from 2019 and 2020 from Walmart US.  These data sources were then cleaned and joined in Pandas and then pushed to an SQL database. The cleaning of the data took us from 30,000 records to a little over 400.    

Using Flask we retrieved our data from the SQL server using Python and SQLAlchemy and then used JavaScript, CSS, D3, HTML, CanvasJS (for our JS library not covered in class), Plotly, and Bootstrap to render our charts from the data.

Our data is represented in a bar chart, pie chart, and box and whiskers chart using CanvasJs.  We also used Plotly for an additional bar chart as well as a bubble chart.  

D3, JavaScript, and CSS were used in our price comparison user interface creating two drop down menus that revealed 2019 vs 2020 prices and populated a data chart of available information about the product selected.   Additionally, links are generated that take you to the current listing to see live price points for the selected product.  

Two tables were also created to display top product price changes that experienced decreases comparing it to top product price changes that experienced increases.  

Our solution to this problem is a full stack solution utilizing data, databases, a dashboard, and visualizations.  
