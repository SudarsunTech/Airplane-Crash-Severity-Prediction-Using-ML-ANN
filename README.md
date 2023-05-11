# Airplane-Crash-Severity-Prediction-Using-ML-ANN

Fatalities and severe injuries caused due to vehicle accidents have been among the most unpredictable happenings and elusive cases that might occur anywhere in the world. Aviation is a subset of these accident types that are far more difficult to investigate and are typically left off as speculations or mysteries in this project. Regarding the topic, this research focuses on previous aircraft accidents and trains a few algorithms to determine which one can accurately forecast the severity of the provided incidents, so that it can be used to anticipate real-life accident circumstances in the future. 
An implementation of a few well-known prediction algorithms will be taken forward in forecasting the severity of Airplane Accidents, with details gathered from the Federal Aviation Administration (FAA) accidents and incidents data from Kaggle. Artificial Neural Networks (ANN), Logistic Regression, Support Vector Machines (SVM), and Nave Bayes are the algorithms or methodologies that will be used, tested, and compared. 
This research and implementation can also help in predicting the most likely causes of that particular severity level of an accident, allowing us to work on these issues to reduce accident severities or uncertainty in the aviation sector.

**Data Source**

The Airplane Accidents Severity Dataset available on Kaggle contains information about airplane accidents that occurred from 2010 to 2018. The dataset contains two CSV files, "train.csv" and "test.csv".
The "train.csv" file contains 10,000 rows and 13 columns, while the "test.csv" file contains 2,725 rows and 12 columns. Each row in the dataset represents a unique airplane accident incident. The columns in the dataset include:
1. "Accident_ID": A unique identifier for each accident incident.
2. "Accident_Type_Code": A code representing the type of accident (e.g., "1" for "Controlled Flight Into Terrain", "2" for "Loss of Control In Flight", etc.).
3. "Cabin_Temperature": The temperature inside the cabin at the time of the accident (in degrees Celsius).
4. "Turbulence_In_gforces": The g-force experienced by the aircraft during the accident.
9
5. "Control_Metric": A metric representing the pilot's control of the aircraft during the accident.
6. "Total_Safety_Complaints": The number of safety complaints reported for the airline operating the flight in the 12 months prior to the accident.
7. "Days_Since_Inspection": The number of days since the aircraft was last inspected.
8. "Safety_Score": A score representing the overall safety performance of the airline operating the flight.
9. "Severity": The severity of the accident (i.e., "Minor_Damage_And_Injuries", "Significant_Damage_And_Fatalities", "Significant_Damage_And_Serious_Injuries", or "Highly_Fatal_And_Damaging").
10. "Accident_Type_Description": A description of the accident type.
11. "Max_Elevation": The maximum altitude reached by the aircraft during the flight.
12. "Violations": The number of safety violations reported for the airline operating the flight in the 12 months prior to the accident.
13. "Adverse_Weather_Metric": A metric representing the weather conditions at the time of the accident.
