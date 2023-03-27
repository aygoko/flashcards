# Flashcards Application

This is a command-line application for creating and practicing flashcards. 

The application allows users to add, remove, import and export flashcards, as well as quiz themselves on the flashcards they have created. 

The application also keeps track of errors and logs user activity.

## Installation
To install the application, you will need to have [Go](https://go.dev/) installed on your machine. Once you have installed Go, follow the steps below:

Clone the repository to your machine:


```
git clone https://github.com/username/flashcards.git
```
Replace username with your GitHub username.


Navigate to the cloned repository:

```
cd flashcards
```
Build the application:
```
go build
```
Run the application:

```
./flashcards
```
## Usage
When you run the application, you will be presented with a menu that allows you to perform various actions:

* **Add**: Add a new flashcard to the deck.

* **Remove**: Remove an existing flashcard from the deck.

* **Import**: Import flashcards from a JSON file.

* **Export**: Export flashcards to a JSON file.

* **Ask**: Quiz yourself on the flashcards in the deck.

* **Log**: Print the log of user activity.

* **Hardest card**: Print the flashcard(s) with the highest error count.

* **Reset stats**: Reset the error count for all flashcards.

* ** Exit**: Exit the application.

## Data Persistence
The flashcards are stored in memory while the application is running. 

If you want to persist the flashcards across multiple sessions, you can use the import and export commands to load and save the flashcards to a JSON file.

## License
The application is open-source software released under the MIT license.
