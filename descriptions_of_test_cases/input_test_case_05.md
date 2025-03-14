# Test Case 5

## Description
Invalid inputs for teams and putting the same number for the home and away teams.

## Inputs
```
1: "3"
2: "BYU"
3: "Y"
4: "Cosmo"
5: "UVU"
6: "N"
7: "Utah State"
8: "N"
9: "asdf"
10: "4"
11: "2"
12: "2"
13: "exit"
14: "exit"
```

## Expected Input Prompts
```
1: "Enter the number of soccer teams you want to enter (at least 2): "
2: "Enter a name for team 1: "
3: "Enter Y if team 1 is sponsored, otherwise enter N (or anything else): "
4: "Enter the name of your sponsor: "
5: "Enter a name for team 2: "
6: "Enter Y if team 2 is sponsored, otherwise enter N (or anything else): "
7: "Enter a name for team 3: "
8: "Enter Y if team 3 is sponsored, otherwise enter N (or anything else): "
9: "Enter the team number of the HOME team or enter "exit" to end the season: "
10: "Enter the team number of the AWAY team or enter "exit" to end the season: "
11: "Enter an option: "
```

## Expected Printed Messages
```
1: "1: BYU"
2: "2: UVU"
3: "3: Utah State"
4: "Invalid team number! Try again."
5: "You can't choose the same team as the home and away team! Try again."
6: "The soccer season is over!"
7: "Postseason Menu:"
8: "1: Go to Team Info Menu"
9: "2: Go to Game Info Menu"
10: "exit: End the program"
11: "Exiting the program."
```

## Example Output **(combined Inputs, Input Prompts, and Printed Messages)**
```
Enter the number of soccer teams you want to enter (at least 2): 3
Enter a name for team 1: BYU
Enter Y if team 1 is sponsored, otherwise enter N (or anything else): Y
Enter the name of your sponsor: Cosmo
Enter a name for team 2: UVU
Enter Y if team 2 is sponsored, otherwise enter N (or anything else): N
Enter a name for team 3: Utah State
Enter Y if team 3 is sponsored, otherwise enter N (or anything else): N
1: BYU
2: UVU
3: Utah State
Enter the team number of the HOME team or enter "exit" to end the season: asdf
Invalid team number! Try again.

1: BYU
2: UVU
3: Utah State
Enter the team number of the HOME team or enter "exit" to end the season: 4
Invalid team number! Try again.

1: BYU
2: UVU
3: Utah State
Enter the team number of the HOME team or enter "exit" to end the season: 2
Enter the team number of the AWAY team or enter "exit" to end the season: 2
You can't choose the same team as the home and away team! Try again.
1: BYU
2: UVU
3: Utah State
Enter the team number of the HOME team or enter "exit" to end the season: exit

The soccer season is over!
Postseason Menu:
1: Go to Team Info Menu
2: Go to Game Info Menu
exit: End the program

Enter an option: exit
Exiting the program.
```
