# India_Covid-19_Status
Data analysis of India Covid-19 data 
This dataset contains latest Covid-19 India state-wise data as on July 25, 2021. This dataset can be used to analyze covid condition in India. This dataset is great for Exploratory Data Analysis.Covid-19 status gives information about the impact of deadly disease in India.


Source : https://www.mygov.in/covid-19
Analysis of India Covid-19 Status dataset


# Dataset

The dataset used for this project was found on Kaggle. The basic idea of analyzing the India Covid-19 dataset is to get a fair idea about how each state is affected by Covid-19. With each day increasing number of cases is increasing possibility of infections amongst healthy people of the state is also increasing. It is however difficult to understand how to stop virus spread. Most of the affected patients are recovering. This recovery rate is different for different states. The dataset contains state wise data of affected and recovered patient’s data.

. This kind of analysis can be done using the data, by studying the factors such as

• Most affected state in India by Covid-19

• Survival rate of patients

• Total active cases from state

# Tools & Libraries

• Python • Jupyter Notebook • Pandas • Numpy • Seaborn • Matplotlib • Plotly & Cufflinks

# Data Description

The dataset contains the following Columns:
• State/UTs : Name of the State
• Total Cases: Total cases from state
• Active: Total active cases in State
• Discharged : Total number of people recovered from Covid-19 and sent back home
• Deaths: Total deaths from state due to Covid-19 infection.
• Active Ratio (%): Ratio of total number of affected people Vs currently active patients.
• Discharge Ratio (%): Ratio of total number of affected people Vs discharged patients 
• Death Ratio (%): Ratio of total number of affected people Vs patients died due to infection.

# Data Cleaning

I made the following changes and created the following variables:

• Deleted the columns URL, address and phone as they were not important for analysis

• Removed Duplicate Rows

• Checked for null values in given data.

# EDA

I looked at the different-different trends of the data and below is highlights of the analysis.

• Overview of Active cases out of Total cases in given state 

• Nationwide impact at one glance

• State wise total cases of Covid-19 patients.

• Total cases Vs death ratio for each state

• State wise death percentage

• Recovery rate of each state population

• State wise total survivor of Covid-19

• Data overview to understand entire impact at a glance

• The existing dataset does not give idea about total state population and affected people due to Covid-19 virus infection. To get exact impact of Covid-19 in state additional State Population data needs to be added.
