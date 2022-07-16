# Covid-19-Dataset-Analysis with Excel
This is my first analysis as a data analyst (in view), with dashboard visualization.
---
## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)


## Introduction

## Problem Statement
The aim, objective and purpose of this project on Covid-19 is to create awareness, insights and information concerning Covid-19. 
This project will be visualizing the impact and havoc it has caused in the whole of the world. This includes different cases from the confirmed cases to the death cases, to the rate and the recovered cases of people with Covid-19.
It wil be visualizing top 5 countries with covid-19 prevalence, bottom 5 countries with covid-19 prevalence, top 5 countries with the highest number of people that has recovered from the so called covid-19, with top 5 countries that have highest death rate.
The objective of this project is to find out how COVID-19 has really affected countries in the world.

---

## Data Sourcing
I got the Covid-19 dataset through 'web scraping' on GitHub. There is a feature on Excel that allow you to import your dataset from 'The Web', the term is called 'scraping', when you scrap a dataset from a source you literally just 'collect' the dataset, rather than just downloading the dataset to your local machine(laptop).

<img width="867" alt="Capture" src="https://user-images.githubusercontent.com/88210780/178150472-7f2d4976-e324-4deb-befd-d7953c8ac173.PNG">

When you observe the above visual closely, you will notice that there are different things that looks interesting and explorable in it.
First if all, the dataset is a time series, and a time series is a series of values of a quantity obtained at successive times, often with equal intervals between them. You will also noticed that it has automated updates(the dataset updates itself automatically so far there is new data). The dataset lastly has datasets for confirmed cases for US and globally likewise same for death cases, it's only recovered cases that doesn't have US dataset separately.
So, proceeding I clicked on the 'confirmed global cases' firstly to scrape it as shown below, and rather than downloading it, I "View raw".

<img width="885" alt="Capture1" src="https://user-images.githubusercontent.com/88210780/178151001-5c248a4c-a413-468c-a950-c569e40ff721.PNG">

So, after viewing it, I copy the whole link as seen below;

![Screenshot (32)](https://user-images.githubusercontent.com/88210780/178509277-d732e134-5cdf-4636-9645-34ca10b8e38e.png)

After copying the link, I headed to my Excel 365 to import my scraped data as seen below;

<img width="399" alt="Capture2" src="https://user-images.githubusercontent.com/88210780/178510221-9119f5bc-5767-4047-8a50-4be110d572da.PNG">

Then,

<img width="503" alt="Capture3" src="https://user-images.githubusercontent.com/88210780/178510287-47970e00-d602-4fb0-9f83-de4375446a4b.PNG">

Then boom!
I was taking to 'Power Query Editor', an extension environment of MS Excel, a place where #Data_Transformation takes place. 

---

## Data Cleaning/Transformation

Now moving to the real deal, # Data Transformation. Here is where all the cleaning of my dataset will be done.
