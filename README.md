# Random

From now on I will write whatever I have learned here date wise and topic wise:

👉To take input from user,in browser we use prompt() while in CLI,we use ReadlineSync (a package).
Most of the tools in a programmers toolkit is CLI: github, shell, programming language repls etc. are all CLIs. In strictest terms, if you are interacting with a program via command line (that black thing with text on it which hackers use in movies) then it's a CLI (Command Line INTERFACE).

var readlineSync = require('readline-sync');
 
// Wait for user's response.
var userName = readlineSync.question('May I have your name? ');
console.log('Hi ' + userName + '!');
