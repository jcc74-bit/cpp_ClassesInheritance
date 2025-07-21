# cpp_ClassesInheritance

## one major thing in the curriculum for both cpp and java is inheritance and classes. I spent most of second semester learning about classes. 

### Constructor: The first introduction to classes

#### We made transcripts for imaginary students and used constructors to organize them nd introudce us.

### Animal Zoo: Testing out inheritance with different animals inheriting traits from the animal class. 

### Point Line Triangle: uses classes and methods to find distance, points, area etc

### Car rental:  A Car class that represents a car in a rental system with the following attributes and methods:

#### Attributes:
##### licensePlate (string): Unique identifier for the car.
##### model (string): Car model (e.g., Toyota Corolla).
##### year (int): Manufacturing year of the car.
##### rentedStatus (bool): Indicates whether the car is currently rented.
##### rentalPricePerDay (double): Cost of renting the car per day.
##### mileage (double): The total distance the car has been driven.

#### Methods:
##### Constructor to initialize the car with license plate, model, year, rental price, and mileage.
##### Getters to retrieve car information.
##### Setters to update mileage and rental price.
##### rentCar(): Sets rentedStatus to true if the car is available.
##### returnCar(double additionalMileage): Marks the car as available again and updates the mileage.
##### displayCarInfo(): Prints all details of the car.
