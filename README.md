# Exercise: Vehicle Rental Management System in Ruby

## Objective

Develop a system to manage vehicle rentals, including cars, motorcycles, and trucks, as well as to control clients and the rentals made.

## Part 1: Basic Vehicle Structure

### Vehicle

Base class for vehicles. It should contain attributes such as `make`, `model`, `year`, `mileage`, and `status` (available, rented, in maintenance).

### Car

Inherits from `Vehicle` and adds specific attributes for cars, like `fuel type` and `number of seats`.

### Motorcycle

Inherits from `Vehicle` and adds specific attributes for motorcycles, such as `engine displacement` and `start type` (electric, kickstart).

### Truck

Inherits from `Vehicle` and adds specific attributes for trucks, like `load capacity` and `cabin type`.

## Part 2: Rental Management

### Client

A class with attributes like `name`, `driver's license number (CNH)`, `contact information`, and a rental history.

### Rental

A class representing a rental contract, containing the `client`, `vehicle`, `start date`, `end date`, and `rental value`.

### Rental Shop

A class that manages the vehicles and the rentals. It should allow adding and removing vehicles, registering rentals, and listing vehicles available for rental.

## Part 3: Advanced Features

### Polymorphism

Implement methods in a polymorphic way in the subclasses of `Vehicle` to calculate the rental cost, which may vary according to the type of vehicle, mileage driven, and rental duration.

### Exceptions

Use exceptions to handle cases such as attempting to rent an unavailable vehicle, or attempting to return a vehicle not rented from the shop.

### Modules

Create modules for shared behaviors among classes, such as a `Verifiable` module that offers methods to verify the validity of the client's driver's license or a vehicle's availability for rental.

## Extra Challenge

Implement a scoring system for clients, where each rental adds points based on the duration and the type of vehicle rented. Clients can use accumulated points for discounts on future rentals.

This exercise offers an opportunity to apply and deepen your Ruby knowledge, focusing on Object-Oriented Programming. You will work with inheritance, polymorphism, exceptions, and modules, besides practicing the design of a complex and interactive system. Good luck!
