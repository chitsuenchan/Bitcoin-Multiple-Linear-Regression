# Bitcoin - Multiple Linear Regression 
<img src="ExampleScreenshots/0.jpg" height="400">

**Table of Contents**
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Dependent Variable](#dependentvariable)
- [Independent Variables](#independentvariables)
- [Data Exploration](#dataexploration)
- [Data Preparation](#datapreparation)
- [Predictive Models](#predictivemodels)
- [Results](#results)

## Introduction <a name="introduction"></a>
Supervised machine learning to create a model that predicts the Bitcoin price.

Please download the PDF in this repo for more detail. Below only gives a brief overview.

## Motivation <a name="motivation"></a>
This was a paper I wrote during my Masters degree which achieved 90% the highest on the course. I was highly motivated in this project due to my interest in statistics, maths, and using machine learning to make predictions.

## Data Sources <a name="features"></a>
- Coindesk
- Thomson Reuters
- Tor Metrics
- Google Trends
- Federal Reserve

## Dependent Variable <a name="dependentvariable"></a>
* Bitcoin/USD Spot Rate

## Independent Variable (Features) <a name="independentvariables"></a>
* Coindesk
  * Daily Bitcoin transactions
  * Difficulty mining Bitcoin
  * Total number of Bitcoins in circulation
* Thomson Reuters
  * Gold spot price
  * Oil spot price
  * Euro/USD spot price
  * GBP/USD spot price
* Federal Reserve
  * Effective federal funds rate
* Google
  * Google searches for Bitcoin
* Tor Metrics
  * Total number of Tor clients 

## Data Exploration <a name="dataexploration"></a>

### Correlation Between Variables
<img src="ExampleScreenshots/1.jpg" height="400">

### Summary Statistics
<img src="ExampleScreenshots/2.jpg" height="400">

### Standard Deviations and IQR
<img src="ExampleScreenshots/3.jpg" height="450">

### Time Series - Variable Percentage Change
<img src="ExampleScreenshots/4.jpg" height="450">

### Time Series - Bitcoin against Google Searches and Tor Clients
<img src="ExampleScreenshots/5.jpg" height="550">

## Data Preparation <a name="datapreparation"></a>
### Data cleaning
* Took first difference to ensure variables are on the same scale
* Filled in missing values for Google Trends by duplicating weekly values to whole week
* Date range adjusted to ensure all variables are within scope

### Histogram - Showcasing effects of first difference transformation
<img src="ExampleScreenshots/8.jpg" height="900">

## Predictive Models <a name="predictivemodels"></a>
<img src="ExampleScreenshots/6.jpg" height="250">

## Results <a name="results"></a>
<img src="ExampleScreenshots/7.jpg" height="1000">
