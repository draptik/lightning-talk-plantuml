``` sh
Vehicle <|- Car

Car          *-     Wheel   : has 4 >
Person "0.." -- "1" Car     : owns >
Driver       -      Vehicle : drives >

interface Vehicle
interface Driver

Vehicle : +getSpeed()
Car : #weight : double
```
![hello](resources/uml-class-demo-05.svg)
