

| RTC                   | Will be true when time is feeding time otherwise false |
| --------------------- | ------------------------------------------------------ |
| Bowl Weight Sensor    | Will be true when there is food in the bowl            |
| Food Hopper Sensor    | Will be true when the food hopper i empty              |
| Manual Overide button | Will be true when pressed                              |
|                       |                                                        |


| RTC | Bowl Weight Sensor | Food Storage Sensor | Manual Overide button |     | Open Hopper | Error State |
| --- | ------------------ | ------------------- | --------------------- | --- | ----------- | ----------- |
| 0   | 0                  | 0                   | 0                     |     | 0           | 0           |
| 0   | 0                  | 0                   | 1                     |     | 1           | 0           |
| 0   | 0                  | 1                   | 0                     |     | 0           | 1           |
| 0   | 0                  | 1                   | 1                     |     | 0           | 1           |
| 0   | 1                  | 0                   | 0                     |     | 0           | 1           |
| 0   | 1                  | 0                   | 1                     |     | 1           | 1           |
| 0   | 1                  | 1                   | 0                     |     | 0           | 1           |
| 0   | 1                  | 1                   | 1                     |     | 0           | 1           |
| 1   | 0                  | 0                   | 0                     |     | 1           | 0           |
| 1   | 0                  | 0                   | 1                     |     | 1           | 0           |
| 1   | 0                  | 1                   | 0                     |     | 0           | 1           |
| 1   | 0                  | 1                   | 1                     |     | 0           | 1           |
| 1   | 1                  | 0                   | 0                     |     | 0           | 1           |
| 1   | 1                  | 0                   | 1                     |     | 1           | 0           |
| 1   | 1                  | 1                   | 0                     |     | 0           | 1           |
| 1   | 1                  | 1                   | 1                     |     | 0           | 1           |