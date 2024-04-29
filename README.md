<h1>COVID-19 Data-Analysis</h1>


<h2>Description</h2>
In this research endeavor, an extensive examination of COVID-19 data obtained from "OUR WORLD IN DATA". Through meticulous data cleaning and analysis procedures, critical metrics including total cases, total fatalities, mortality rates, and infection rates were thoroughly investigated. Employing advanced data visualization techniques, attention was drawn to the top 10 nations exhibiting the highest rates of mortality and infection, alongside an exploration of trends on a continental scale. These findings furnish valuable insights into the global and regional ramifications of the COVID-19 pandemic, offering a nuanced understanding of its impact on different parts of the world.
<br />


<h2>Utilities Used</h2>

- <b>SQL</b> 
- <b>Power BI</b>

<h2>Environments Used </h2>

- <b>SQL Server </b> (Windows 10)
<h2>How Dashboard looks like: </h2>
<p align="center">
<img src="https://imgur.com/kqYh7ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Program walk-through:</h2>
<h2>1.Data Retrieval & Data Cleaning: </h2>
is an essential part of any analysis project unnessary columns were removed followed by replacing null values with zero to avoid discontinous results. A seperate column containg year of reported data was made in-order to check the year-wise trend in pandemic also procedures to handle missing values, duplicates, and inconsistencies in the dataset were carried out.
<br />
<br />
<p align="center">
Removing unnecesary columns: <br/>
<img src="https://imgur.com/1J5jcws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Replacing null vlues with zero: <br/>
<img src="https://imgur.com/gdhIw1n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Adding a column for Year:  <br/>
<img src="https://imgur.com/enIoa6k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>1.Data Processing: </h2>
The data suggested that the total number of people infected eith the covid 19 were 1.96bn. with Lativia,Nauru,Australia,Niue showing highest infection rate. also the death count was 4.91M.
<br />
<br />
 <p align="center">
 World wide infection rate:  <br/>
<img src="https://imgur.com/RL5FMt0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
10 countries with highest infection rate: <br/>
<img src="https://imgur.com/aJrVjjd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Total Death count: <br/>
<img src="https://imgur.com/9Zw4htd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Year wise death count:  <br/>
<img src="https://imgur.com/OCY8G4q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
10 countries with highest Death count:  <br/>
<img src="https://imgur.com/LlR4C6w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Total Number of people vaccinated per year:  <br/>
<img src="https://imgur.com/K9fryC3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2>Insights</h2>
<h2>1.Top 10 Countries Analysis: </h2>
Identified the ten countries with the highest infection rates and death counts during specific time periods.<br />
Analyzed temporal trends and variations in infection rates and death counts using Power BI visualizations in bar graph.<br />
Peru has the highest death rate among all the countries while Lativa has highest infection rate.<br />
<h2>2.Geographical Distribution Analysis:</h2>
Visualized the effect of COVID-19 across different geographical regions.Which tells about the death rate and infection rate across different regions of the world and this helps to understand the intensity of impact according to the different climate and many other factors.<br />
It is clear from the pie chart the effect of COVID-19 was highest in Europe with a value of 32%. and asia holds second position with 28% over all effect. <br />
<h2>Vaccination Progress Tracking:</h2>
Year wise distribution of vaccination was vsualized using power bi.<br />
which sows a relationship between infection rates and mortality data. Data shows that number od vaccinaton is quite high in 2022 and 2023.<br /> 
Also death rate by year wise distribution was calculated and it shoes that 2021 has highest death rate which is also deaclared as year of COVID-19.<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
