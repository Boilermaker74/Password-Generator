# Password-Generator
A program that will generate a random password to a user's specifications

Changed title from document to password generator.

Remove the comment status from the CSS program link for styling.

Added onclick tag which directs the password link function in JavaScript. If the user presses the button, the JavaScript file initiates a random password generator program.

The JavaScript file first prompts the user for a password length via a windows prompt. The value is confirmed to be between 8 and 128 characters. If not, a widow prompt is displayed with the character length given by the user. Once confirmed by the user, they are redirected to the password length prompt.

Once the password length has been confirmed, the Java program then moves on to prompt the user to describe the criteria of the password. There are 4 characteristics of the password that the user can choose from: uppercase, lowercase, numerical and special characters.

The user is presented with each one of these criteria separately and given the opportunity via window alert to either include the criteria or not. Once all the criteria have been considered, the program confirms via window alert the password character length and each of the criteria used in the password.

If the user makes a mistake and does not choose any criteria at all, the program will inform the user via a windows alert and direct them back to the beginning of the program.

The program uses a random generator algorithm that was taken in part from a web page and modified: https://www.geeksforgeeks.org/how-to-generate-a-random-password-using-javascript/.

Once the program has created a password, it is stored in a array via the unshift command and printed to the HTML program via the replace document.body.innerHTMLdocument.body.innerHTML.replace() tag. The new password is pushed to the array via the unshift command and subsequently each password is stored in the elements of the array with the newest password always in element 0.

The user then has the option to create a new password simply by pressing the button again. This can be repeated to generate as many passwords as the user desires. 

The user exits the program by closing the web page.

The use of special characters was problematic as some of them would crash the code. I was unable to determine which characters were at issue, so I just used a truncated list to accomplish the task.

Thank you.
