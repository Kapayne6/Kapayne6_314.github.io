---
title: API
---

## Individual API
| **API**       | **Byte #1** | **Byte #2**  |
|---------------| ----------- | ------------ |
| Variable Name | Motor Start | Sensor Start |
| Variable Type | uint8_t     | uint8_t      |
| Min Value     | 0           | 0            |
| Max Value     | 1           | 1            |
| Example       | 1           | 0            |

Our teams message structure is simple as our goal is to communicate starting and stopping actions at the individual level using 1's and 0's. We will only send a signal of a 1 or a 0 to a teammate once it is their turn in the order to begin their operation, and all other actions
will be halted until the individual completes their task.
