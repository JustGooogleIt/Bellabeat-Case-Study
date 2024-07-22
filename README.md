# Bellabeat-Case-Study

Author: Ashwin Subramanian

Date: June 26th 2024

## Introduction

Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.

## Scenario

You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat executive team along with your high-level recommendations for Bellabeat’s marketing strategy.

## Business Task

Sršen asks you to analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart devices. She then wants you to select one Bellabeat product to apply these insights to in your presentation.

The following three points are the questions that need to be answered by this analysis.

1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

### Prepare

The dataset used for analysis is from Kaggle ([https://www.kaggle.com/datasets/arashnic/fitbit?resource=download](url)). It contains 18 CSV files with data provided by thrirty three eligible FitBit users. The users consented to the submission of personal tracker data and the data set that they created is now publically available. There are however a couple of limitations. The data is vastly outdated with the dataset only being updated in February of 2024 but the data was originally being collected back in 2016. Additionally data was only being collected for a grand total of 31 days from the dates of 04/12/2016 to 05/12/2016. Moreover the sample size is extremely small as only 33 respondents replied to the survey and there is no gender description making it harder for us to apply our insights solely to Bellabeat's female target market reducing the relevance of the data. 

### Process

Initially I started by cleaning the data. The first step that was taken was to merge all of the hourly activities into a single spreadsheet through excel in order to more easily work with the data. Following that the datasets were loaded into the Microsoft SQL Server. During this process there were certain hiccups such as datatypes being loaded incorrectly. Afterwards I loaded the dataset the Microsoft SQL Servers where again I faced another issue of the values loading as strings instead of FLoats or Integers. Fixing that I also converted ActivityDate into date format using datetime. A detailed process of the data cleaning procedure can be found in the CleaningFitbase File.


