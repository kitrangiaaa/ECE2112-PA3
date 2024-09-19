#### <center> WELCOME TO MY EXPERIMENT 3!
## <center> PYTHON DATA ANALYSIS (PANDAS)

Name: Trangia, Klein Isshi G.

Section: 2ECE-D

Date Submitted: September 19, 2024¶

## __BEFORE I START THE PROBLEM__

First, I input "import pandas as pd" to access the pandas library.

<img width="169" alt="Screenshot 2024-09-19 at 12 54 49 PM" src="https://github.com/user-attachments/assets/bf0ad197-4d91-43f1-8f79-5177f06688a2">

## __PROBLEM 1__
### __a. Load the corresponding .csv file into a data frame named cars using pandas__

I used "cars" to store the cars.csv file and print it so it can be read in the following codes.

<img width="260" alt="Screenshot 2024-09-19 at 12 57 07 PM" src="https://github.com/user-attachments/assets/f0583025-7f76-43d6-bebc-8b8b49df5d67">

And this is the output for the Problem 1 - letter a:

<img width="450" alt="Screenshot 2024-09-19 at 1 01 49 PM" src="https://github.com/user-attachments/assets/453350dd-2e7f-4aa7-b2f4-3318d7dc1f6c">

 ### __b. Display the first five and last five rows of the resulting cars.__

To display the first five rows and the last five rows, I used these codes:

<img width="119" alt="Screenshot 2024-09-19 at 1 04 58 PM" src="https://github.com/user-attachments/assets/3347e75a-9bff-4cf2-8911-d5fc30592d37">

<img width="117" alt="Screenshot 2024-09-19 at 1 05 17 PM" src="https://github.com/user-attachments/assets/0346b757-8fa9-4b69-8ed5-662683076d40">

Heads will serve as the first half of a table, and tails will serve as the last half of a table. The number inside the parenthesis will be the number of rows you want to print; rows start with 0 when counting. 

Output for the first five rows:

<img width="599" alt="Screenshot 2024-09-19 at 1 10 55 PM" src="https://github.com/user-attachments/assets/6943ddfc-fd53-4254-965c-3324052bd4df">

and output for the last five rows:

<img width="579" alt="Screenshot 2024-09-19 at 1 11 49 PM" src="https://github.com/user-attachments/assets/93588a85-2719-4f22-9b67-6643a7bcbe0c">

## __PROBLEM 2__

 ### __a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7…) of cars.__

 To display the first five rows with odd-numbered columns, I used this code:
 
<img width="165" alt="Screenshot 2024-09-19 at 1 14 19 PM" src="https://github.com/user-attachments/assets/30b8825e-7f99-456a-964a-c6c13d002204">

I used .iloc so it would be easy to determine the rows and columns needed for the question. 0:5 is the row, meaning the first five rows, and 0::2 is the column, meaning it will start at 0, not including the models, only that it will get the pattern of the odd.

This is the output of the code:

<img width="345" alt="Screenshot 2024-09-19 at 1 21 14 PM" src="https://github.com/user-attachments/assets/d87a8f56-c846-47b5-8310-88b10f2c2f09">

### __b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.__

To display the row of Mazda RX4, I used the code:

<img width="92" alt="Screenshot 2024-09-19 at 1 24 51 PM" src="https://github.com/user-attachments/assets/010e002b-0e0c-4388-b37a-689d354ee914">

This code is for rows only; 0:1 means it will start at 0 and will stop and not print 1.

This is the output for this code:

<img width="533" alt="Screenshot 2024-09-19 at 1 27 37 PM" src="https://github.com/user-attachments/assets/39722441-aa55-4f82-abb5-5682df11df50">

### __c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?__

To display the cylinders with the car model, I used this code:

<img width="257" alt="Screenshot 2024-09-19 at 1 30 04 PM" src="https://github.com/user-attachments/assets/05fef038-eabe-4b30-9222-287f39dda8fc">

I used .loc because names of the rows and columns use it, so I would just locate the row of Camaro Z28, which is 23, and input the ones I need to display, which are model and cyl.

This is the output:

<img width="154" alt="Screenshot 2024-09-19 at 1 35 24 PM" src="https://github.com/user-attachments/assets/2632c1ed-a381-4779-8ee2-9cb10444b247">

### __d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4 Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.__

In this last letter, to display the cylinders and gear type of each asked model, I used this code:

<img width="352" alt="Screenshot 2024-09-19 at 1 38 23 PM" src="https://github.com/user-attachments/assets/ff47741c-c90c-42b6-b190-fcd6faed8633">

I used .loc again to specifically input the rows I needed and the ones I needed to display, which are the cylinders and the gear type of Mazda RX4 Wag, Ford Pantera L, and Honda Civic.

This it the output of my last code:

<img width="350" alt="Screenshot 2024-09-19 at 1 44 31 PM" src="https://github.com/user-attachments/assets/4ae3beb1-0a52-4548-9f34-28fa68f2f4c4">

## __MESSAGE__
Thank you for finishing my journey in this programming assignment 3!
