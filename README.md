# Paraulogic_autosolver

by *[Gerard Domenech Domingo]*


## Content
- [Project Description](#project-description)
- [Future Work](#future-work)
- [Workflow](#workflow)


## Project Description 

I did this little project just for fun and to practice my skills on web scrapping and python language in general.

Run the notebook to watch how the famous daily Paraulogic game is solved word by word in your screen!

## Future Work

- Try to reduce the time that it takes to solve the game, by eliminating conjugated verbs maybe using NLP.
- Look for a better dictionary source


## Workflow

First I tried to create the autosolver by using only BeautifulSoup, but realized later that Selenium should be used to input the solutions.

To check for real words, I downloaded a list of word from http://escrable.montane.cat/diccionari/ which is a dedicated site to the game "Scrabble" in catalan language. Then i filtered this list with the conditions stablished by Paraulogic rules.
