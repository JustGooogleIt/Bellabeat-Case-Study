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

## Prepare

The dataset used for analysis is from Kaggle ([https://www.kaggle.com/datasets/arashnic/fitbit?resource=download](url)). It contains 18 CSV files with data provided by thrirty three eligible FitBit users. The users consented to the submission of personal tracker data and the data set that they created is now publically available. There are however a couple of limitations. The data is vastly outdated with the dataset only being updated in February of 2024 but the data was originally being collected back in 2016. Additionally data was only being collected for a grand total of 31 days from the dates of 04/12/2016 to 05/12/2016. Moreover the sample size is extremely small as only 33 respondents replied to the survey and there is no gender description making it harder for us to apply our insights solely to Bellabeat's female target market reducing the relevance of the data. 

## Process

Initially I started by cleaning the data. The first step that was taken was to merge all of the hourly activities into a single spreadsheet through excel in order to more easily work with the data. Following that the datasets were loaded into the Microsoft SQL Server. During this process there were certain hiccups such as datatypes being loaded incorrectly. Afterwards I loaded the dataset the Microsoft SQL Servers where again I faced another issue of the values loading as strings instead of FLoats or Integers. Fixing that I also converted ActivityDate into date format using datetime. A detailed process of the data cleaning procedure can be found in the CleaningFitbase File.


## Results

The data analysis revealed that most respondents consistently used health tracking devices, averaging 20 hours and 18 minutes per day over a span of 29 days. All respondents tracked various health metrics, including calories, steps, physical activity, and the duration of these activities. Notably, 72% of respondents monitored their sleeping patterns, 42% tracked their heart rate, and only 24% measured their weight. Despite this tracking, respondents spent a significant amount of time inactive, averaging 8 hours and 50 minutes per day. The analysis also showed that respondents were most active in the afternoon, from 17:00 to just before 20:00, and during midday, from 12:00 to just before 15:00. On average, they recorded 7,600 steps per day, which falls short of the recommended daily steps. Interestingly, respondents who tracked their sleep received the recommended amount of rest, averaging more than 7 hours per night. Among those who monitored their heart rate, 42% maintained a normal heart rate, though there were minor spikes observed, with a minimum of 36 BPM and a maximum of 203 BPM.

## Analysis

The analysis suggests that users engage with health tracking devices throughout the day, not just during workouts at the gym. This insight indicates that Bellabeat's marketing campaign should emphasize not only the health benefits of their products but also the beauty and style they offer, positioning them as fashionable accessories. Additionally, Bellabeat can highlight the importance of protecting clients' private information, as these devices are deeply integrated into their daily lives. Since most users of health devices are young adults, leveraging social media as an advertising platform could be highly effective. Advertising efforts could be strategically timed for the early morning, when people are preparing for work, and in the afternoon, as they leave work and head to the gym.

## Reccomendations

Bellabeat can enhance its offerings and attract more clients by implementing several key features. Firstly, they can launch health campaigns that encourage a healthy lifestyle, providing clients with comprehensive health information that illustrates how different metrics work together. Emphasizing the importance of tracking heart rate, Bellabeat could also offer alerts when certain thresholds are exceeded, and even provide the option to link devices to medical services in the event of an imminent heart attack. Additionally, the company could send training reminders at times when users are typically most active, helping to support regular exercise routines. To further enhance user experience, ensuring that their devices have long-lasting batteries would allow users to track their health for extended periods without interruption.
