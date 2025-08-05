## 1) Problem
Automated pet feeder that will; feed cats and dogs at scheduled time,  check if the food had been eaten and how much, alert staff if there is an issue with the system
## 2) IO 

| **Type**      | **Component**          | **Purpose**                                                                           | **Data Type** | **Data Format / Example**                                    | Other infomation  |
| ------------- | ---------------------- | ------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------ | ----------------- |
| **Input**     | RTC                    | Triggers actions based on time schedule                                               | datetime      | `2025-08-05`, `13:00`                                        |                   |
| **Input**     | Bowl Weight Sensor     | Measures how much food is in the bowl before/after dispensing and eating              | int/float     | Grams                                                        |                   |
| ~~**Input**~~ | ~~Animal Sensor~~      | ~~Detects animal presence and type (can be extended to identify individual animals)~~ | ~~boolean~~   | ~~true/false. Animal in range = true. out of range = false~~ |                   |
| **Input**     | Food Hopper Sensor     | Measures remaining food in hopper                                                     | int/float     | Grams                                                        |                   |
| **Input**     | Manual Override Button | Allows manual feeding trigger and testing                                             | boolean       | `true` / `false`                                             |                   |
| **Input**     | User Controls          | Controls how much food is being dispensed, scheduled feeding time                     | list          |                                                              | [[User Controls]] |
| **Output**    | Food Dispenser Servo   | Activates to release food                                                             | boolean       | `true` = dispense, `false` = idle                            |                   |
| **Output**    | Staff Alert System     | Notifies staff of errors or unusual behaviour                                         | boolean       | `true` = alert, `false` = no alert                           |                   |
| **Output**    | Feeding Log            | Stores feeding records for monitoring, debugging                                      | list          |                                                              | [[Log Example]]   |


## 3) Plan Algorithm / logic and solution

Food will dispense at specific times defined by the user and stored as "Feeding_Time"
The amount of food to be dispense will be defined by the user and stored as "Feed_Amount"



[[Truth Table]]





## 4) implementation

## 5) test & Refine