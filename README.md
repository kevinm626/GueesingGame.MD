# GuessingGame.MD
 ```mermaid
flowchart TB
A[Main]-->B[Integer Secret Number]-->C[Integer UserGuess]-->D[Secret number = Random #  1-10]-->E[/Output - Please guess a number between  1-10\]-->F[\Input User Guess/]-->G[/User Guess SecretNumber/]-->|False|H[/Output - Please enter a number between 0-9\]-->I[Input user Guess]
G-->|True|J[Correct! Thanks for playing]
I-->G
```
