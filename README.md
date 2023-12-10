My AirBnB_clone group Project

=====Project Description=====
This project is an Airbnb clone console application, designed to mimic some
of the functionalities of the Airbnb platform.
The console provides a command-line interface for users to interact with the application,
allowing them to manage property listings, bookings, and user accounts.

Command Interpreter Description
The command interpreter is a Python-based console application that serves as the interface
for managing the Airbnb clone.
It allows users to execute various commands to perform actions such as adding properties,
making bookings, and interacting with user accounts.

To start the Airbnb clone console, follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/your-username/airbnb-clone-console.git

2. Navigate to the project directory:
cd airbnb-clone-console

3. Run the command interpreter:
./console.py

How to Use
The command interpreter supports a variety of commands to perform different actions. Here are some examples:
1. To add a new property
create Place city_id="your-city-id" user_id="your-user-id" name="Your Place Name"
2. To list all available properties:
all Place
3. To make a booking:
book Place your-place-id user_id="your-user-id"

Examples
1. Adding a Property
$ ./console.py
(hbnb) create Place city_id="123" user_id="456" name="Cozy Apartment"

2. Listing all PropertiesListing all Properties
$ ./console.py
(hbnb) all Place

3. Making a Booking
$ ./console.py
(hbnb) book Place 789 user_id="123"
