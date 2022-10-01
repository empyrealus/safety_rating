![A logo that may not show](https://phyziro.com/images/PhyziroLogo.png)
# Driver Safety Ratings (DSR)

# Abstract: 
Provide a composite score for the purposes of indicating as to whether a driver is a *safe* driver or not.

This score would adjust similar to a credit rating; as time passes and data is appended, the users driver rating will change overtime.


# Mission Statement

Providing a standardized industry base score for the sakes of faciliting transparent pricing, affordability and incentivizing safe driving to reduce the liklihood of someone engaging in risky driving behavior.

For insurance insurance should follow people and not specifically the car; a user with multiple cars should __not__ need multiple policies.


# Mission Objective

Provide a __Driver Safety Rating (DSR)__ for companies and drivers -- similar to a credit score


Faciliate insurance solutions for all incomes and situations to prevent drivers from going uninsured or underinsured due to a malformed insurance algorithms producing inconsiderate prices.


|**Proposed Features**|Feature Description|
|:--|:--|
|Driving score weighted against intoxcation levels| Know the likelihood of some person X causing some incident Y, while intoxicated at Z level.
|Financial capability| Leveraging income or DTI(Debt-To-Income ratio), etc. to determing maximum policy affordable and adjusting policy to fit clients budget, to reduce the odds of a lapse in policy.

Drivers will be able to improve this score overtime and this score may be affected by a variety of factors.

__Note__

> A driver should **never** be denied coverage or charged so excessively that coverage be deemed unobtainable, when using the score profile to assess liability.


# Features Format and View in Tubular format


|Drivers_Name|Geo_location|Global_Positioning|Age|Gender|Relationship|Children|Education_Level|Education_Specializtion|Annual_Income|Debt|DTI_ratio|Intoxication_risk|Disability|Vision|Criminal_History|Criminal_Status|Auto_Claims_for_Bodily_Injury|Auto_Claims_for_Property_Damage|Auto_Claims_for_uninsured_motorist_bodily_injury|Auto_Claims_for_comprehensive|Auto_Claims_for_collission|Miles_driven|GPS_Trackable|
|:--|:--|:-|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
|Alyssa Doe|Houston, Tx|28.361136640146" N, 81.5087592601776" W|24|Female|Married|5|Bachelor|Arts|300000|33777|0.11259|0.09|None|2020|None|None|0|0|0|0|0|3400|False|


--
Use Cases Table
--
|Case #|Type|Psuedo Statement|Use|
|:--|:--|:--|:--|
|1|INSERT| INSERT INTO {table} (Drivers_Name,Geo_Location,Age,etc.) VALUES ({Name},{Location},{Age},etc.)|Insert a new user|
|2|UDPATE|SELECT Drivers_Name FROM {table} WHERE EXISTS (UPDATE Drivers_Name WHERE Drivers_Name == {Name}) | Update the name of the user|
|3|DELETE|SELECT Drivers_Name FROM {table} WHERE EXISTS (DELETE FROM {table} WHERE Drivers_Name == {Name})| Delete Driver (would delete based upon unique identifier rather than name)|
|4|INSERT|@|7|
|5|UDPATE|@|7|
|6|DELETE|@|7|
|7|INSERT|@|7|
|8|UDPATE|@|7|
|9|DELETE|@|7|
|10|INSERT|@|7|
|11|UDPATE|@|7|
|12|DELETE|@|7|
|13|INSERT|@|7|
|14|UDPATE|@|7|
|15|DELETE|@|7|
|16|INSERT|@|7|
|17|UDPATE|@|7|
|18|DELETE|@|7|
|19|INSERT|@|7|
|20|UDPATE|@|7|
|21|DELETE|@|7|


---
Team
---
Team Name: Variant
Rickey L. Hargrove Jr.

Roberto ____ Jr.
