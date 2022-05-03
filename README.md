# C-_FULL_PROJECT
Car rentals are essential for increasing the mobility of vehicles while decreasing the total number of cars used. In this project, it’s required to develop car rental management software. The program should be able to save the information about the renters (drivers) as well as the cars.
The program should have the
following modules:
• Import/export renters’ data
• Import/export cars’ data
• Add/ Remove car data
• Add/ Remove driver data
• List the available cars.
• Rent a car
The implementation of the project can be done in the following parts:
Part 1:
The file “driversData.csv” contains the data of the customers that rented cars
before. Use this file to create an array that holds the customers’ information
(National ID, Name, Age, Gender, License Number, etc..). You can either represent
the data as a Multidimensional array or an array/vector of Objects (of course you
would first have to create the Renter Class first).
Part 2:
The file “carsData.csv” contains the cars’ data. The main information needed to
be recorded is car model, license plates number, owner, and renter. The data of
each car is also can be represented as an array/vector of car objects.
Checkpoint: After implementing the classes, test part 1 and part 2 by making sure
you can import the data, save it to the array of objects, and export it again to the
files without problems.
Part 3:
Implement a module to add/remove data from the cars or renters’ arrays and
save the updated data to the files. The user should be asked to input all necessary
data for creating a new car or renter object as described above.
Part 4:
Implement a function that lists all the available cars for rent. Also, implement
another function to list all the rented cars with the basic information of the car
and the full name of the renter.
Part 5:
Implement a module to choose a certain car using its license number and assign a
renter to it. The renter should be either exist on the database or added to it
before renting the car. The renter should be identified using the national ID. 
