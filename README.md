# Project: Investigate No-show appointments - Dataset

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Questions to ask:
 
 1- Is SMS_recieved associated with no_show?
 
 2- What period is covered by this dataset (survey) and does the time between scheldule day and appointment day affect the patient's no-show ?
 
 3-  What is the percentage that patients no-show for there appointmen?
 
 4-  Is age associated with patient  no-show?

## Conclusions
> This Dataset has a Lot to investigate, we can't make sure what are the most important features affecting the result of not showing up on the scheduled appointments, we can assuem that if we have 62,299 patients booked 110,527 appointments in 40 days It is a normal thing of life that 20.2% of appointments be no-show. SMS help alittle patient to remember the appointment and newborns get more carring. also it's helpful to make the appintment few days before.

## Limitaion
> We don't have enough data about neiborhood and the geography of the hospital.

> Many patinets booked more than one appointment (max = 88 means one patient make 88 appointment) and that mislead some of results, that's make the nature of the personality as a factor or technical issues while booking. 