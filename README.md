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


|UiD|Drivers_Name|Geo_location|Global_Positioning|Age|Gender|Relationship|Children|Education_Level|Education_Specializtion|Annual_Income|Debt|DTI_ratio|Intoxication_risk|Disability|Vision|Criminal_History|Criminal_Status|Auto_Claims_for_Bodily_Injury|Auto_Claims_for_Property_Damage|Auto_Claims_for_uninsured_motorist_bodily_injury|Auto_Claims_for_comprehensive|Auto_Claims_for_collission|Miles_driven|GPS_Trackable|
|:--|:--|:-|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
|777143932|Alyssa Doe|Houston, Tx|28.361136640146" N, 81.5087592601776" W|24|Female|Married|5|Bachelor|Arts|300000|33777|0.11259|0.09|None|2020|None|None|0|0|0|0|0|3400|False|


--
Use Cases Table
--
|Case #|Type|Psuedo Statement|Use|
|:--|:--|:--|:--|
|1|INSERT| INSERT INTO {table} (Drivers_Name,Geo_Location,Age,etc.) VALUES ({Name},{Location},{Age},etc.)|Insert a new user|
|2|UDPATE| CREATE PROCEDURE Select_Driver AS SELECT Drivers_Name FROM {table} WHERE state = @state GO; EXEC Select_Driver @state = EXISTS (UPDATE {table} SET Drivers_Name = 'Alyssa Doe' WHERE UiD == {iD}) | Update the name of the user (__expiremental/not-tested__ SQL)|
|3|DELETE|EXEC Select_Driver @state = EXISTS (DELETE FROM {table} WHERE UiD == {iD})| (__Experimental Non-tested__)Delete Driver |
|4|INSERT| Default value is 0, when table is built. There is no insert to perform.  | Add new miles driven|
|5|UDPATE| CREATE INDEX driver_mileage ON {table} (Miles_driven); UPDATE {table} SET Miles_driven = SUM({new_miles}+{old_miles}) | Update the number of miles driven|
|6|DELETE|@| We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|
|7|INSERT|@|7|
|8|UDPATE|@|7|
|9|DELETE|@|We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|
|10|INSERT|@|7|
|11|UDPATE|@|7|
|12|DELETE|@|We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|
|13|INSERT|@|7|
|14|UDPATE|@|7|
|15|DELETE|@|We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|
|16|INSERT|@|7|
|17|UDPATE|@|7|
|18|DELETE|@|We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|
|19|INSERT|@|7|
|20|UDPATE|@|7|
|21|DELETE|@|We only want to perform a delete record on the driver. Since all data is related to the driver, we will perform an UPDATE to reset the values to their default, instead of DELETE.|


---
Team
---
Team Name: Variant
Rickey L. Hargrove Jr.

Roberto ____ Jr.
