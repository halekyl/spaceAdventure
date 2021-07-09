# spaceAdventure
Dart command-line program that takes in a path to a JSON file as the command-line argument. The program prints the output and supports interaction with the user via the command-line. 

In the flutter sdk file run `export PATH="$PATH:`pwd`/flutter/bin"`\
To start the program: `dart bin/main.dart bin/planetarySystem.json`

## Does the following:

- Prints a greeting including the name of the planetary system (JSON) and the number of planets in the system.
- Prompts the user for thier name. 
- Echoes back the user's name.
- Prompts the user to make a choice about traveling to a random planet or not.
- Re-prompts the user repeatedly until they enter Y or N.
#### If Y: (user chooses to travel to a random planet)
- Selects a random planet and print its name and description.
#### If N: (user chooses not to travel to a random planet)
- Prompts the user to enter the name of a planet they want to travel to.
- Displays the name and description of the planet that the user specified.
- Validation is implemented to handle the case where the user enters the name of a planet that is not in the JSON data file.

At the end of the interaction the program terminates.
