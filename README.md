# crossword

This crossword puzzel solver is the first iteration and can be refactored for efficiency.
It uses try except blocks to catch and handle out-of-bounds situation. When the word is found it will give you the coordinates of the first letter of the word. The technique I use is to first find all the coordinates of the first letter and save them in list. When the search begins the coords of the first letter is passed in to the search algorithm; it's done this way so the algorithm does not have to search the entire list every time.
