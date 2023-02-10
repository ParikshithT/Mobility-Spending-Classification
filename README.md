# Mobility-Spending-Classification

## Problem Setting:
The problem that was selected for analysis involves predicting the consumer spending behavior based on human mobility measures.
During initial stages of COVID-19, a greater number of people are tested as COVID positive. The main reason for this is not knowing how coronavirus is transmitted. After finding that coronavirus spreads between people through direct, indirect (through contaminated objects or surfaces), or close contact with infected people via mouth and nose secretions, government suggested people maintain at least 1metre distance from each other and to self – quarantine. This impacted the consumer spending behavior as most of the work places and shops are closed. The seven models, if successfully created and implemented, could potentially help in understanding the pattern of spending in this pandemic.

## Problem Definition:
In this project, the problem is to find how mobility measures impact consumer spending by building models, one for each of the response variables: spend_acf, spend_aer, spend_apg, spend_tws, spend_all_inchigh, spend_all_incmiddle, spend_all_inclow using mobility attributes as input variables. The main objective of the project is analyze and compare the performance of seven models.

## Data Sources:
The mobility variables indicate how visits to places, such as grocery stores and parks, are changing in each geographic region are provided by Google -https://www.google.com/covid19/mobility/.
The consumer spending measures are provided by affinity solutions and are used in opportunity insights database https://github.com/OpportunityInsights/EconomicTracker. For this project use the encoded dataset mobility-spending-encoded.csv. The encoded dataset has 1s and 0s introduced in the variables related to consumer spending. All values less than -0.1 are replaced by 0s. Similarly, all values greater than -0.1 are replaced by 1s. A 0 indicates a large drop in consumer spending and a 1 indicates a small drop in consumer spending.
