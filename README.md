### OOP Design Challenge

**Inheritance:**
Base Class: Vehicle 
1st Class: Car
2nd Class: Motorcycle
This shows inheritance because both Car and Motorcycle share common data and behavior from Vehicle while adding their specific features.

**Interface Implementation:**
Interface: Drivable
Class: Car
This demonstrates that the Car class has promised to fulfill the contract of being “drivable” by implementing the interface.

**Polymorphism:**
1st Example: Method Overriding
Both Car and Motorcycle override the abstract method startEngine() from Vehicle to provide type-specific engine starting behavior.
2nd Example: Method Overloading
In the Vehicle class, the accelerate() method is overloaded. One version accepts a single parameter (increment), and another version accepts two parameters (increment and duration) to calculate speed change differently.

**Data Coupling:**
Example: updateSpeed(int newSpeed) in class Vehicle
This is an example of data coupling where only a single primitive value is passed between methods.

**Stamp Coupling:**
Example: updateVehicleInfo(VehicleInfo info) in class Car
This demonstrates stamp coupling because the method receives a whole object (a data structure) rather than individual primitives.
