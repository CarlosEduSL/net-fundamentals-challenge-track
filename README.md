# DIO - .NET Track - Fundamentals  
www.dio.me  

## Project Challenge  
For this challenge, you will need to use the knowledge acquired in the fundamentals module of the DIO .NET track.  

## Context  
You have been hired to build a system for a parking lot, which will be used to manage parked vehicles and perform operations such as adding a vehicle, removing a vehicle (and displaying the fee charged during the period), and listing the vehicles.  

## Proposal  
You will need to build a class called "ParkingLot" following the diagram below:  
![Parking Lot Class Diagram](diagrama_classe_estacionamento.png)  

The class contains three variables:  

**initialPrice**: Decimal type. It is the fee charged for parking a vehicle.  

**pricePerHour**: Decimal type. It is the hourly rate for keeping the vehicle parked.  

**vehicles**: A list of strings representing a collection of parked vehicles. It only contains the license plate of the vehicle.  

The class contains three methods:  

**AddVehicle**: Method responsible for receiving a license plate entered by the user and storing it in the **vehicles** variable.  

**RemoveVehicle**: Method responsible for checking if a specific vehicle is parked, and if so, it will ask for the number of hours it stayed in the parking lot. After that, it performs the following calculation: **initialPrice** + (**pricePerHour** * hours), displaying it to the user.  

**ListVehicles**: Lists all vehicles currently in the parking lot. If there are none, display the message "There are no parked vehicles."  

Finally, an interactive menu should be created with the following implemented actions:  
1. Register vehicle  
2. Remove vehicle  
3. List vehicles  
4. Exit  

## Solution  
The code is halfway done, and you must continue implementing it according to the rules described above so that we end up with a functional program. Look for the commented word "TODO" in the code, then implement it according to the rules above.
