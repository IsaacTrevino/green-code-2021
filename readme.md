Team Sustain
Code Green 2021

Readme:-
We used Aurora Postgres SQL DB and data ingestion pattern that is established from S3 to our postgres aurora DB to feed a UI Application.
Same S3 Data is used for ML Module for Predictive Analysis. 
We levaraged amazon sage maker funcitonality of autopilot to train our 3 data sets.
Our 3 data sets are air emissions, water consumption, and waste management. We massaged the data before it enters S3 with aws location services to populate the longtitude and latitude 
Once the data was masaged, we have two entry points one with static dataset, and the other with ml/ai predective model
This data is then exposed with AWS API Gateway and lambda functions to show both static data, and the predictive analysis on a realtime map
This solution will help in all areas of sustainbility by addressing climate restrictions and solutions we can adminster for better handling of our sustainbility for the longterm.
Collapse

