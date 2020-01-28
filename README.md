# DevDataGenerator

The DevDataGenerator allows a user to quickly and easily produce a pdf file containing a github account, depending on the input submitted, through the Command Line Interface.

# Getting Started

When the program is ran by node in the CLI, the user will be prompted to enter the username of the github account they are inquiring about.

 After the username is submitted, they will be asked for their favorite color for increased visual affect (4 options). When a color option is selected, the program will make an AJAX call to the github API, returning data on the github user (if a valid username is submitted).
 
  If a valid username is entered, a pdf will be produced with the background color matching the previously chosen option. Once the pdf is produced, the program stops running.

  # Built With

  -Javascript
  -Node
  -HTML

  # User Story  
```
AS A product manager

I WANT a developer profile generator

SO THAT I can easily prepare reports for stakeholders
```
# Business Context

For managers with employees to keep records on, the ability to quickly view and prepare part of their portfolio can certainly be convenient. Instead of surfing the github website for individual accounts, a manager would be able to use this application for the same effect.