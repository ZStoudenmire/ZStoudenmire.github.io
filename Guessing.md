flowchart TB
    A[Guess a number between 1 and 50] --> B(Correct?)
    B --> C{Yes!}
    B --> D{No!}
    C --> E[You win!]
    D --> F[Try again!]
    D --> G[Must guess a number between 1 and 50!]
