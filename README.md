# EDA - Carsale Advertisement Dataset
Exploratory data analysis using Python, Numpy, Pandas, Seaborn

<h2>Table of Contents</h2>
<ul><li>Problem Statement</li>
<li>Data Loading and Description</li>
<li>Data Profiling</li>
<li>Understanding the Dataset</li>
<li>Profiling_1</li>
<li>Preprocessing_1</li>
<li>Profiling_2</li>
<li>Preprocessing_2</li>
<li>Post Profiling</li>
<li>Conclusions</li></ul>

<h2>Problem Statement</h2>
<p>The notebooks explores the basic use of Pandas and will cover the basic commands of Exploratory Data Analysis(EDA) which includes cleaning, munging, combining, reshaping, slicing, dicing, and transforming data for analysis purpose.</p>

<ul><h3>Exploratory Data Analysis<h3>
<p>Understand the data by EDA and derive simple models with Pandas as baseline. EDA ia a critical and first step in analyzing the data and we do this for below reasons :</p>
  <li>Finding patterns in Data</li>
<li>Determining relationships in Data</li>
<li>Checking of assumptions</li>
<li>Preliminary selection of appropriate models</li>
<li>Detection of mistakes</li></ul>

<h2>Data Loading and Description</h2>

<ul><li>The dataset consists information collected from car sale advertisements for study/practice purpose where most of them're used cars.</li>
<li>The dataset comprises of 9576 observations of 10 columns. Below is a table showing names of all the columns and their description.</li></ul><br><br>
<table><tbody><th>Column Name</th>	<th>Description</th>
  <tr><td>car</td>	<td>Manufacturer brand</td></tr>
  <tr><td>price</td>	<td>	Seller’s price in advertisement (in USD)</td></tr>
  <tr><td>body	</td><td>Car body type</td></tr>
<tr><td>mileage	</td><td>as mentioned in advertisement (‘000 Km)</td></tr>
<tr><td>engV	</td><td>rounded engine volume (‘000 cubic cm)</td></tr>
<tr><td>engType	</td><td>type of fuel (“Other” in this case should be treated as NA)</td></tr>
<tr><td>registration	</td><td>whether car registered in Ukraine or not</td></tr>
<tr><td>year	</td><td>year of production</td></tr>
<tr><td>model	</td><td>specific model name</td></tr>
  <tr><td>drive	</td><td>drive type</td></tr></tbody></table>
  <br<br>
<h3>Some Background Information</h3>
<ul><li>This data was collected from private car sale advertisements in Ukraine and provided by INSAID team to perform Exploratory Data Analysis.</li>
  <li>This dataset has real raw data which has all inconvenient moments (as NA’s for example).</li>
<li>This dataset contains data for more than 9.5K cars sale in Ukraine. Most of them are used cars so it opens the possibility to analyze features related to car operation.</li></ul>

<h2>--><a href="https://github.com/rohinegi548/EDA---Carsale-Advertisement-Dataset/blob/master/EDA_CarsaleAdvertisement.ipynb">Python notebook is here</a></h2>
