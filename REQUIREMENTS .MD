# Autonomous Delivery Robot - Requirements

| Req ID | Description | Priority |
|---|---|---|
| R1 | The robot shall remain in the **IDLE** state after being switched on and wait for a delivery request. | High |
| R2 | The robot shall start navigating toward the destination when a valid **delivery request is received**. | High |
| R3 | The robot shall continuously monitor its surroundings while navigating. | High |
| R4 | The robot shall enter **AVOIDING_OBSTACLE** when an obstacle is detected during navigation. | High |
| R5 | The robot shall resume navigation toward the destination after successfully avoiding the obstacle. | High |
| R6 | The robot shall start the delivery process when it reaches the destination. | High |
| R7 | The robot shall start returning to the warehouse after the package is successfully delivered. | High |
| R8 | The robot shall stop its current delivery journey and return to the warehouse when the battery becomes critically low. | High |
| R9 | The robot shall become **IDLE** after reaching the warehouse and wait for another delivery request. | High |
| R10 | The robot shall not enter **DELIVERING** directly from **IDLE** or while in **AVOIDING_OBSTACLE**; it must first navigate to the destination. | High |
