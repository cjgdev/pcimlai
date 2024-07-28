# Datasheet

## Motivation

- For what purpose was the dataset created? 
  - The dataset was created to develop a Support Vector Machine (SVM) model for predicting podium winners of Formula 1 races.
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?
  - The dataset was created by Christopher Gilbert using data from the Ergast Developer API. The project was self-funded and conducted independently.

## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
  - The instances represent individual Formula 1 race results, including driver performance, race conditions, and other relevant features.
- How many instances of each type are there? 
  - The dataset includes race results from 1950 to current day, with each instance representing a single race event. The exact number of instances depends on the number of races included in the dataset.
- Is there any missing data?
  - Some driver names and team names may be missing or inconsistent due to variations in data quality from the Ergast API. Missing data was handled during preprocessing.
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
  - No, the dataset does not contain any confidential data. All data is publicly available through the Ergast Developer API.

## Collection process

- How was the data acquired? 
  - The data was acquired using the Ergast Developer API, which provides historical Formula 1 race data.
- If the data is a sample of a larger subset, what was the sampling strategy? 
  - The data represents a comprehensive collection of Formula 1 race results available through the API, without any specific sampling strategy.
- Over what time frame was the data collected?
  - The data spans multiple Formula 1 seasons, from 1950 to 2024.

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
  - Yes, preprocessing steps included handling missing values, normalizing numerical features, encoding categorical variables, and creating new features based on existing data (e.g., driver performance metrics).
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
  - Yes, the raw data was saved to allow for future reprocessing and to support unanticipated future uses.

## Uses

- What other tasks could the dataset be used for? 
  - The dataset could be used for other predictive modeling tasks, such as predicting race outcomes, driver performance, or team performance. It could also be used for exploratory data analysis and visualization of Formula 1 race trends.
- Is there anything about the composition of the dataset or the way it was collected and preprocessed that might impact future uses?
  - The dataset's reliance on historical data from the Ergast Developer API means that any changes or updates to the API could impact future data collection. Additionally, the preprocessing steps taken may need to be adjusted for different modeling tasks or analysis purposes.
