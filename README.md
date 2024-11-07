# State traffic lights of Gishushu junction.
The traffic light system in Gishushu, Kigali manages the flow of vehicles on two intersecting roads:
1. Road 1 (East-West) 
2. Road 2 (North-South).
   
The system operates with four primary states, each defined by the colors of the traffic lights:
- Green
- Yellow
- Red
  
 In **State 1**, Road 1 is Green while Road 2 is Red. After a set time, it transitions to **State 2**, where Road 1 turns Yellow and Road 2 stays Red. Next, in **State 3**, Road 1 turns Red while Road 2 turns Green.
 Finally, in **State 4**, Road 2 turns Yellow and Road 1 remains Red. After the Yellow light on Road 2, the system resets to **State 1**. This cycle ensures smooth traffic flow and prevents collisions at the intersection. The state transitions are triggered by timers, ensuring a regular flow between the two roads.

![Traffic lights state diagram](/Gishush-traffic.png)
