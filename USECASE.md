### USE CASE

### Verbs

|Names            |LDM           | Explenation |
|-----------------|:------------:|-------------|
|Identified |-|
|Invole one or more guest|-|
|Include more than one room|-|
|May not be greater than|-|
|Only be booked in connection with a stay|(x)|
|Can not be used for accommodation|-|
|Should be marked with "late arrival"|-|
|Tasks should be handled by the web application|-|
|Show a list of vacant hotel rooms|x|
|Should include hotel information and type of rooms|-|
|Make a booking|x|
|Include af meeting room|x|
|An error message should be returned|-|
|See a booking (passport)|x|
|Cancel a booking (passport)|x|


## Main Use Case

### Agency employee makes a booking

Main Success Scenario: 
Agency employee makes successfull booking through an booking api.

Prime actor: Travel agency employee / thrird part solution users
Secondary Actor: NONE

1. Actor can get a list of vacant hotel rooms in a given city for a given number of guests and period of time.
2. Actor can make a booking for up to 9 persons in one or more rooms for a given period of time on a given day
3. See booking

* * *


Secondary Scenario Nr. 1:
Pre-conditions: 
Agency employee cancell a booking. 

1. Actor can get a list of vacant hotel rooms in a given city for a given number of guests and period of time.
2. Actor can make a booking for up to 9 persons in one or more rooms for a given period of time on a given day
3. Actor makes a booking of a meeting room
4. See booking


Secondary Scenario Nr. 2:
Pre-conditions: Must have a booking
Agency employee cancell a booking. 

1. Actor finds booking
2. Actor cancels the booking
