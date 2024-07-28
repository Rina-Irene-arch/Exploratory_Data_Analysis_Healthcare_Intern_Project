# Exploratory Data Analysis Healthcare Intern Project
This repository contains an internship project focused on Exploratory Data Analysis (EDA) of smartwatch-collected physiological data. The goal is to investigate the potential for detecting and alerting users to drowsiness based on their biometric information.

Project Overview
Exploring Drowsiness Patterns in Wearable Device Data
- **Background**: A wearable technology company produces smartwatches with vital signs sensors. These sensors monitor heart rate and PPG (Photoplethysmography) signals, which include variations in green, red, and infrared light. One of the key features of the company's smartwatch is its ability to detect and alert users to potential drowsiness based on their physiological data.

- **Objective**: The task is to perform an Exploratory Data Analysis (EDA) on a dataset collected from these smartwatches. The dataset includes various physiological parameters along with a 'drowsiness' label, which indicates the level of sleepiness based on an adapted Karolinska Sleepiness Scale (KSS).

**Dataset Description**:
https://www.kaggle.com/datasets/vitoraugustx/drowsiness-dataset
- The dataset was created using a Galaxy Watch4 smartwatch vital signs sensors. Data were collected from heart rate and PPG sensors (PPG includes 3 variations, green, red and infrared). The 'drowsiness' column refers to the label assigned by the user based on an adaptation of the Karolinska Sleepiness Scale (KSS).
- Labels range from 0.0 to 2.0, where 0.0 represents level 1 on the KSS scale (Alert), 1.0 corresponds to level 6 (Some signs of sleepiness), and 2.0 indicates level 8 (Sleepy, but some effort to stay awake).
- Columns:
  - heartRate: Heart rate readings from the smartwatch sensors.
  - ppgGreen, ppgRed, ppgIR: PPG (Photoplethysmography) sensor readings in green, red, and infrared wavelengths respectively.
  - drowsiness: Label indicating the level of drowsiness based on an adapted Karolinska Sleepiness Scale (KSS). Values range from 0.0 to 2.0, where 0.0 represents alertness and 2.0 represents significant drowsiness

 





