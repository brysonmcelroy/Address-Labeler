# Exercise 1.1 - Address Labeller

In this assignment, you will write a program that correctly formats a Canadian address for a letter.

## Requirements

Your program will ask the user for the following information (in this order):
* Last name
* First name
* Street
* House number
* Postal code
* City
* Province

The program should print out the address label in the format below:

```
John Doe
123 Main St
Chatham, ON  N7L 1B6
```

Things that must be included:
* First and last name on the first line
* Street address (house number and street) on the second line
* City, province and postal code on the third line.  The city must have a comma and space after it.  The province and postal code must be separated by two spaces.

### Sample Executions

Use these samples to test your code and make sure that your formatting is correct.

**Sample #1**
```
Enter the last name: Devet
Enter the first name: Casey
Enter the street: Grand Ave W
Enter the house number: 85
Enter the postal code: N7L 1B6
Enter the city: Chatham
Enter the province: Ontario

Casey Devet
85 Grand Ave W
Chatham, Ontario  N7L 1B6
```

**Sample #2**
```
Enter the last name: Claus
Enter the first name: Santa
Enter the street: Reindeer Rd
Enter the house number: 1
Enter the postal code: H0H 0H0
Enter the city: North Pole
Enter the province: Nunavut

Santa Claus
1 Reindeer Rd
North Pole, Nunavut  H0H 0H0
```

## Submitting

When you are finished, push your code to GitHub.  Submit it on [Gradescope](gradescope.com) where it will be tested automatically for correctness and graded manually for style (see [Style Guide](https://mrdevet.github.io/ICS3C/assignments/Style-Guide/)).