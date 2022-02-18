# SNHU Grazioso Rescue Animal Final Project
## Overview
You have been newly assigned to a development team at Global Rain. This team is currently working on a project for an innovative international search and rescue animal training company, Grazioso Salvare. Grazioso Salvare currently uses dogs as search and rescue animals. They expect to begin training monkeys as search and rescue animals as well. A portion of the work on this project has already been done. Your team lead has assigned you to create one new class and modify the existing driver class in the software application.
## Tasks
### Create a Monkey Class that:
- Inherits from the RescueAnimal class
- Includes monkey-specific attributes
- Includes mutator and accessor methods for each attribute
### Complete the Driver Class
#### Add a menu loop that:
- Displays the (included) menu
- Prompts the user for input and validates the input
- Takes the appropriate action based on the input
#### Complete a method to intake a new dog that:
- Prompts the user for input and validates the input
- Sets data for all attributes
- Adds the newly instantiated dog to an ArrayList
#### Implement a method to intake a new monkey that:
- Prompts the user for input and validates based on monkey name and
species type
- Sets data for all attributes
- Adds the newly instantiated monkey to an ArrayList
#### Implement a method to reserve an animal that:
- Prompts the user for input
- If animal matches input criteria: Accesses animal object from ArrayList
and updates the ‘reserved’ attribute of the animal
- If no animal matches input criteria: Prints feedback to the user
#### Implement a method to print (display) information about the animals that:
- Prints a list of all dogs OR all monkeys OR all animals that are “in service”
and available (not “reserved”)
