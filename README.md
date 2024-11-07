Specification of the Gishushu Traffic Light State Machine
Initial State:

The traffic light system begins in an initial state where all traffic is stopped in all directions. This is the starting point for the system.
States:

Red State:
Action: Stops traffic in all directions.
Transition: When the "Red timer expires," the system transitions to the "Green" state.
Green State:
Action: Allows traffic to move in designated directions.
Transition: When the "Green timer expires," the system transitions to the "Yellow" state.
Yellow State:
Action: Prepares to stop traffic in all directions.
Transition: When the "Yellow timer expires," the system transitions back to the "Red" state.
Transitions:

Each state has a specific timer associated with it (Red, Green, and Yellow timers). When a timer expires, the system moves to the next state:
Red to Green: Triggered by the expiration of the Red timer.
Green to Yellow: Triggered by the expiration of the Green timer.
Yellow to Red: Triggered by the expiration of the Yellow timer.
Cycle:

The traffic light system goes through a continuous cycle of Red → Green → Yellow, repeating as each timer expires.
