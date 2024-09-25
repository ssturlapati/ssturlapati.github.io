# Guessing Game Flowchart 
```mermaid
flowchart TD
Start[Start Game!] -.-> Number{Is it the right number?}
    Number -.- NO -.-> ANSWER1[WRONG, THINK ABOUT IT AGAIN!]
    ANSWER1 -.-> CHOICE1[GUESS AGAIN!]
    CHOICE1 -.-> Number
    Number -.- YES -.-.-.-> ANSWER2[CONGRATS, YOU WON!]
```
##
