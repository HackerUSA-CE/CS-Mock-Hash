# Lab: Hashing Passwords with Bcrypt

Please refer to the directions in Canvas.
Activity: Mock Hash
For this activity, feel free to grab a buddy or two. It can be fun to test out passwords together. We'll be taking some existing code that runs on the terminal and allow you to create a user login system.

Setup
Instructions:
Click HERE for the link to the repo.
Fork (not clone) it to your OWN GitHub account.
Now to clone the repo to your machine, click the green 'Code' button and then copy the URL.
In a new terminal, or Git Bash, go to where you want to clone the repo.
Type git clone in the terminal or Git Bash, then a space, then paste the URL you copied from your repo. Example:
undefinedClick here to copy
Hit "Enter" or "Return" whichever is on your keyboard.
In your terminal, run npm install to install the required node_modules.
After the install, run npm start in the terminal.
Do the assignment in Visual Studio Code and stage your changes using git add -A command.
Make at least one commit by using git commit -m "write your message here" command. Example:
undefinedClick here to copy
Finally push your changes using the git push command. Example:
undefinedClick here to copy
Run the command "node index.js".
Part One: Get to know your code.
There's quite a bit of starter code here, so first you will need to familiarize yourself with what it's already doing. Run the following command to see the program run.

undefinedClick here to copy
If you type in the word help when prompted for an action, you will get a list of other commands you can use. Type each different command until you feel comfortable with the program.

help: Show available commands
exit: Quit program
view: Show list of existing users
create: Create a new user
login: Log in to an existing user account
Part Two: Fill in the missing parts.
You'll notice that upon entering the username and password for either the create or login commands, they simply print a message that says they aren't implemented. It's our job now to use the bcrypt package's methods to fill in the blanks.

Directions:
You'll need to use bcrypt's hash method for implementing the hashPassword function.
You'll need to use bcrypt's compare method for implementing the checkPassword function.
You'll need to implement each place in the code that is marked TODO.
Results:
You can print out whichever success and error messages you like. Here is some sample output:

Sample terminal output
Success Criteria:
Creating a user should result in them being put into the globalStore object.
The checkPassword function should have a success message only on a successful password match.
The checkPassword function should have a failure message on an unsuccessful password match.
The program is already set up to run for you. You shouldn't need to alter anything outside the checkPassword and hashPassword functions.

Bonus: Readline
Are you curious about the neat little npm package that allowed us to grab user input from the terminal? It's called readline-sync. Use it to make another piece of functionality for this app that does anything you like.
