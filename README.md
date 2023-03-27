Flashcards 
This is a flashcards game in which the user can add flashcards, remove flashcards, import flashcards, export flashcards, ask questions about flashcards, print the log of previous operations, see the hardest flashcards and reset the statistics.

Requirements
Golang 1.16 or higher
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/example-user/flashcards.git
Change directory to the cloned repository:

bash
Copy code
cd flashcards
To start the program, run:

bash
Copy code
go run main.go
The program will prompt you to enter the number of cards to add.

arduino
Copy code
Input the action (add, remove, import, export, ask, exit, log, hardest card, reset stats):
To add a new card, enter add. The program will then prompt you to enter the number of cards to add. Enter the number and then enter the term and definition of the card.

css
Copy code
Input the number of flashcards:
yaml
Copy code
The card:
yaml
Copy code
The definition of the card:
To remove a card, enter remove. The program will then prompt you to enter the term of the card you want to remove.

Copy code
Which card?
To import cards, enter import. The program will then prompt you to enter the name of the file that contains the cards you want to import.

arduino
Copy code
File name:
To export cards, enter export. The program will then prompt you to enter the name of the file where you want to export the cards.

arduino
Copy code
File name:
To ask questions about the cards, enter ask. The program will randomly select a card and ask you to enter its definition. Enter your answer and the program will tell you if you are correct or not.

bash
Copy code
How many times to ask?
json
Copy code
Print the definition of "word":
yaml
Copy code
Your answer:
To see the log of previous operations, enter log. The program will print the log of previous operations.

arduino
Copy code
Input the action (add, remove, import, export, ask, exit, log, hardest card, reset stats):
To see the hardest cards, enter hardest card. The program will print the cards with the highest error count.

arduino
Copy code
Input the action (add, remove, import, export, ask, exit, log, hardest card, reset stats):
To reset the statistics, enter reset stats.
arduino
Copy code
Input the action (add, remove, import, export, ask, exit, log, hardest card, reset stats):
To exit the program, enter exit. The program will save the cards to a file (if you specified a file when you ran the program) and then exit.
arduino
Copy code
Input the action (add, remove, import, export, ask, exit, log, hardest card, reset sta
