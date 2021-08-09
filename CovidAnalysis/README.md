# COVID-19 Data Exploration and Analysis
This project is focused on analysing and trying to get some insights from the COVID-19 dataset.<br>
The data used to explore in this project can be found [here](https://ourworldindata.org/covid-deaths).

![Dashboard built with Tableau](https://github.com/HenriqueCastros/COVID19-Analysis/blob/main/resources/DashBoard_FrontPage.png?raw=true)

> Dash board built with Tableau available [here](https://public.tableau.com/views/COVID19Analysis_16277580390360/Dashboard1?:language=pt-BR&:display_count=n&:origin=viz_share_link).

### Features to be developed
This project is still in development, there are upcoming updates still to be released. Following are the tasks I plan to implent:

- [x] Data exploration with SQL.
- [ ] Data cleaning with SQL.
- [ ] Data exploration with Pyhton.
- [ ] Data cleaning with Python.
- [x] Build Dashboards with Tableau.

### Prerequisites

Before we begin, you will need a few tools, such as:

- Python, with Pandas, Matplotlib and Scikit-learn installed.
- A database management system of your choice.

### Installing the dataset
In order to export this data to a SQL database, we will firstly download the dataset, do some basic reformatting and then continue to the exploration.<br>
If you want to replicate this procedure at your own computer, please follow the following steps:
1. Go to [ourworldindata.org](https://ourworldindata.org/covid-deaths) and install their data.
2. Open the dataset on Excel (or Google Sheet). Select column **AS** (or 'population') and hit CTRL + X. Go to column **E** (or 'total_cases'), right click on it and select 'Insert Cut Cells'.
3. Delete all columns after **AA** (inclusive). And Save As 'CovidDeaths' .

_**IMPORTANT**: Depending on the DBMS you are using, the file type might be relevant. So be aware if your DBMS can import data from CSV or Excel Files._

4. _Still working on the main dataset, not the CovidDeaths we just created._ Hit CTRL+Z to get back the columns deleted.
5. Select the columns from **E** (or 'population') to **Z** (or weekly_hosp_admissions_per_million) and delete them.
6. Save as 'CovidVaccinations'
7. Import both datasets to SQL with your DBMS.

### Credits
This project was inpired from a series of tutorials, developed by [Alex The Analyst](https://www.youtube.com/channel/UC7cs8q-gJRlGwj4A8OmCmXg). Please check his YouTube channel. I highly recommend.

