# Ashtiani_CSCI2270_FinalProject
Testing repository
Project Members:

Amir Kashipazha
Hamid Ashtiani

﻿Project summary:

For this project we obtained climatological data of Boulder Municipal Airport for 2012 form the National Climatic Data Center (NCDC). These data includes temperature, precipitation, wind speed, wind direction, and could cover. The goal of this project is to:
	1- Calculate Annual, monthly, daily, and hourly information
	2- Find precipitation type like rain, snow, or hail during year
	3- We will add more while working on porject 

Program implementation:

Boulder Municipal Airport station usually records climate data three times per hour. The data we got for 2013 has 25370 lines. We will insert this data on a red-black tree. We will use the time data recorded as key for the tree. 

Program will display menu to user like following:

	1- Annual Summary
	2- Monthly Summary (specif month chosen by user)
	3- Daily Data (for specific day)
	4- Percent of precipitation type (annually and montly)
	5- We will add more option while working on program
	 

Program will have a class which includes:

	1- struct that saves temperature, precipitation, and other climate data
	2- public and private methods: 

		1- read text file
		2- summary for temperature (monthly and annually) 
		3- summary for precipitation (monthly and annually)
		4- wind (monthly and annually)
		5- cloud cover (monthly and annually)
		6- find precipitation type like rain, snow, hail
		7- get climate information for specific day or hour
		8- frozen period 
		9- other functions to create (red-black tree)
