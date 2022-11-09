# Python Hangman Project

A hangman game that allows user to guess what is the fruit that is randomly selected from a word_list. The word_list consist of the following fruits:

* Watermelon
* Honeydew
* Orange
* Mango
* Apple

## Milestone 1 
* Setup of GitHub repository to store project files.

## Milestone 2
* Created a list of fruits and assigning it with the name word_list.
* Import the random module to access the `random.choice()`. This method allow use to randomly select an element from the sequence that is passed it. The element is then assigned to a variable called word.
  
    ```go
     word = random.choice(word_list) 
    ```
* To get user input, the `input()` function is used. The input function also allows custom messages to be displayed when the function is called. Subsequently, the user input is then store in the variable named guess as a string.
  
    ```go
    guess = input("Guess the fruit : ")
    ```
* To check for the length of the user input, an `if` statement is used. If the length of the user input is equals to 1, "Good guess!" will be printed, else "Oops! Input is greater than 1" is printed. 
  
    ```go
    if len(guess) == 1:
        print("Good guess!")
    else:
        print("Oops! Input is greater than 1")
    ```
## Milestone 3
- Added While loop to only allow 1 letter input through.
- Added If statement to check if input letter is in the secret word.
- Created a function for the while loop. 
- Created a function to check if user input letter is in the secret word.

## Milestone 4
- Used OOP to build out the hangman class.
- Created check_guess method to determine if the user's guess is in the word.
- Replace blank underscore with corrently guessed letters
- Deduct lives if guess is incorrect

## Milestone 5
- Added play_game function to run the game.
- Play_game function uses hangman class to create instance
- Added while loop to check for game condition