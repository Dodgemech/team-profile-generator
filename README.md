# Team Profile Generator
## Description
A Node.js application that takes inquirer input and generates an html webpage for teams looking to organize roles.
## Technologies
- HTML
- CSS
- JavaScript
- Node.js
  - Jest
  - Inquirer
- Bootstrap
- Font Awesome
## User Story
```
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```
## Acceptance Criteria
```
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

## Installation
1. Clone the repository to your local machine.
2. In the root directory of you project files, run ```npm i``` to install the required dependecies.
3. In an integrated terminal run the command ```node index.js``` to start the application.
4. Answer all prompts provided.
5. Your HTML file will generate once completed with the prompts in your ```/dist``` folder.
## Screenshot
![127 0 0 1_5500_dist_index html](https://user-images.githubusercontent.com/107086158/197083187-2a7ba2a2-f8c7-46e8-b4c6-7fbbcec5ee9f.png)

## Video Walkthrough
https://drive.google.com/file/d/1lAstLkPxCFSNQnsO-7rjXT948Ks24w9B/view
