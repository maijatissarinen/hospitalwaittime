# Hospital Patient Flow

Personal project that analyzes hospital patient flow and waiting times using PowerBI. Created as a portfolio demonstration to showcase PowerBI skills.
The dashboard shows an overview and more detailed view.

The detailed view states possible problems within the system:
- Anchor doctors have the longest average wait times
- Medicare patients experience longer wait times
- Peak visiting hours in the morning from 8.00 until 11.00
- High patient volumes correlate with longer waiting times

## Data
The data used in this project is obtained from Kaggle and published by user Abdulqader_asiirii. The data is a collection of data from the patient entering the hospital until his exit.

https://www.kaggle.com/datasets/abdulqaderasiirii/hospital-patient-data/data

### Data preparation
- Converting text-based timestamps into DateTime format
- building semantic model in PowerBI Service

### Key metrics
- Average wait time (in minutes)
- 90th percentile wait time
- Total visits
- % of patients seen within 30 minutes of arrival

## Tools used in this project
- Power BI Service
- GitHub (documentation)
- ChatGPT (assignment structure and idea generation)

## Limitations
- Text boxes do not display properly
