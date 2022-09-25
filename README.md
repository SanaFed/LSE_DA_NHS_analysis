# LSE_DA_NHS_analysis
Diagnostic Analysis of the NHS data related to general practitioner (GP) appointments.

25th September 2022

Assignment activity 2: Import and explore the data.

Objectives - familiarise yourself with the data, and determine:

1) How many locations are there in the data set?
2) What are the five locations with the highest number of records?
3) How many service settings, context types, national categories, and appointment statuses are there?

Identified insights and trends:

The dataset consists information about 106 practices in England. The total number of appointments in the dataset is 296.046.770; 15.93% of those appointments belong to 5 GPs with highest number of records (3 out of 5 GPs with highest number of records are in London).

43.95% of all appointments were delivered by practice staff activity under the GMS/PMS/APMS contract; 3.35% of all appointments have no recorded category against an appointment slot type.

85.70% of all appointments involved the patient (‘Care Related Encounter’); 10.95% of all appointments conflict with the description of an appointment; 3.35% of all appointments have no recorded category against an appointment slot type.

10.93% of all appointments were marked as ‘General Consultation Routine’; it equals 12.75% of all appointments which belong to  ‘Care Related Encounter’ category; 3.35% of all appointments have no recorded category against an appointment slot type.

38.90% of all appointments in the provided data set were marked as ‘Attended’; 33.73% of all appointments statuses are marked as ‘Unknown’ (in most cases, at the time of the appointment a ‘Booked’ status will be changed to either ‘Attended’ or ‘DNA’ (Did Not Attend). In some cases, the final status of an appointment remains as ‘Booked’. It is not known from the data whether or not these appointments actually attended. For this reason, the status of these appointments is reported as 'Unknown'.).
