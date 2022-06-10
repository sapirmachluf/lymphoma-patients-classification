# lymphoma-patients-classification

This project addresses the problem of classifying lymphoma patients into groups that represent the length of time they will survive from the moment the disease is discovered, for different age groups. we examine whether a model for all age groups will give at least as good results as dedicated models for each age group. In addition, we also examine the stability of the models. since these are groups with a hierarchy between them, i used multi-label classification models to examine the problem.


## DataSet
The database we used is https://seer.cancer.gov/.
We retrieved the following data:
- Patients with non-Hodgkin's lymphoma
- The patients were first diagnosed before 2015 - in order to match the groups' duration of survival

At the time of execution of this project, the last date on which the database was updated is 2020
