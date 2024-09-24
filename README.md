# GuessingGame.MD
 ```mermaid
flowchart TB
A[Main]-->B[Integer Secret Number]-->C[Integer UserGuess]-->D[Secret number = Random #  1-10]-->E[/Output - Please guess a number between  1-10\]-->F[\Input User Guess/]-->G[/User Guess SecretNumber/]-->|False|H[/Output - Please enter a number between 0-9\]-->I[Input user Guess]
G-->|True|J[Correct! Thanks for playing]
I-->G
```

## How It Works
1. It begins with Booting up the Flowgorithim application
2. The Computer will run the game with assigned value Integers that are named Secret Number _Which the User will attempt to guess_
3. Integer UserGuess, which will be the value entered by the user
4. This then goes to the next value which is the secret number that is assigned a value of a number anywhere between 1-10
5. From there, the Application will generate a text box that will ask to enter a number between 0 and 9. **The reason it is not #'s 1-10 is that in flogorithim the value seleceted represents (n-1)**
6. This is where one of two actions will happen.
   * True - If true, the game will be completed and you will receive a notification in the text box saying "Correct! Thanks for playing"
   * False - If false, The game will output a prompt saying "Please guess a number between  1-10", It will await new input and once entered will keep recycling this function until the correct secret number is chosen.
