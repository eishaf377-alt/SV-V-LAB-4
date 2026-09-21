# Autonomous Delivery Robot - State Model

| State ID | State Name | Description | Entry Condition | Exit Condition |
|---|---|---|---|---|
| S1 | IDLE | Robot waits for a delivery request. | Robot is switched on or reaches the warehouse. | Delivery Request Received |
| S2 | NAVIGATING | Robot moves toward the destination and monitors its surroundings. | Delivery request is received. | Destination Reached, Obstacle Detected, or Critical Battery |
| S3 | AVOIDING_OBSTACLE | Robot temporarily stops normal navigation and avoids the detected obstacle. | Obstacle is detected during navigation. | Obstacle Successfully Avoided |
| S4 | DELIVERING | Robot performs the package delivery process at the destination. | Robot reaches the destination. | Delivery Successful |
| S5 | RETURNING | Robot travels back to the warehouse after delivery or due to critical battery. | Delivery is successful or battery becomes critically low. | Warehouse Reached |

## Events / Conditions

| Event ID | Event / Condition |
|---|---|
| E1 | Delivery Request Received |
| E2 | Destination Reached |
| E3 | Delivery Successful |
| E4 | Warehouse Reached |
| E5 | Obstacle Detected |
| E6 | Obstacle Avoided |
| E7 | Critical Battery |
