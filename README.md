## Word Masters: A Wordle Clone

This is a README.md file for a project that recreates the popular word game Wordle, which we'll call Word Masters.

**What is Word Masters?**

If you're not familiar with Wordle, Word Masters is a game where you try to guess a secret five-letter word within six tries. After each guess, the game provides clues to help you figure out the correct word.

**How to Play:**

1. The game starts with a secret five-letter word chosen at random (or retrieved from an API).
2. You have six guesses to figure out the secret word.
3. After each guess, the game will provide feedback based on your attempt:
    * **Green:** A letter is in the correct position.
    * **Yellow:** A letter is in the word but in the wrong position.
    * **Gray:** The letter is not in the word at all.
4. If you guess the correct word within six tries, you win!

**Demo**

[Word Master Game Link](https://omarzen.github.io/WordMaster/)

**APIs Used (Optional):**

APIs for word selection or validation, include this section:

* **API Name:** [Link to API Documentation]
    * **APIs:** [GET API](https://words.dev-apis.com/word-of-the-day) 
    * **Description:** This will give you the word of the day. It changes every night at midnight
    * **Request/Response Format:** the response will look like this: {"word":"humph","puzzleNumber":3} where the word is the current word of the day and the puzzleNumber is which puzzle of the day it is
 
    * **APIs:** [POST API](https://words.dev-apis.com/validate-word)
    * **Description:** to valdate the word
    * **Request/Response Format:** The API will return back to you the word you sent and validWord which will be true or false. e.g. { "word": "crane", "validWord": true } or { "word": "asdfg", "validWord": false }.

**Contribution Guidelines:**

I encourge you to contribute and make it more beautiful look and make more functional

**Error Handling:**

* Handle a keystroke with a letter.
* Handle a wrong keystroke (like a number or spacebar). Ignore it.
* Handle "Enter" when the word is complete (go to the next line)
* Handle "Enter" when the word is incomplete (ignore it)
* Handle "Backspace" when there's a letter to delete
* Handle "Backspace" when there's no letter to delete

This README provides a basic template to guide the development and documentation of your Word Masters project.
