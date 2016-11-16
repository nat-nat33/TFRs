# Game Code Encryption

## Spectacularly well-written plotline

Brooks is the lead programmer for Fallout 5. He is obviously a very careful person, because people are constantly trying to get information out of him about the game, one way or the other. Brooks gets word that an evil malicious hacker by the name of "Crsn" will be out to steal all of his data and shut down all the servers the next day. Brooks calls up his friend, Tristan, the lead programmer of Persona 6, who also happens to be a top hacker, to encrypt his data. 

## Your Mission 

Help Brooks and Tristan write a program to encrypt the valuable Fallout 5 files and protect them from Crsn. Write a function called `changeChar`, which will take in three parameters. The first will be a given line of text. The second is the letter to be replaced. The third parameter will be the letter replacing it. `changeChar` should replace all instances of a given letter with another letter in a string recursively. 

## Parameters

`lineOfText` - the line of text which you want to have letters replace in 

`charA` - the character you want to be replaced

`charB` - the character you want `charA` to be replaced with

## Return Value

Your function sould return a single string, `lineOfText` with all instances of `charA` replaced with `charB`

## Example function call

`changeChar('Irene is the coolest teacher ever', 'e', 'o')` will return  `"Irono is tho coolost toachor ovor"`

## Important Hints

- Strings have indices too, not just lists
- You can slice both strings and lists, and a quick way of slicing to either end of a list/string is only having the colon:
  - If you want to slice to the end of the list, instead of [5:len(list)] you can use [5:]
  - If you want to slice to the beginning of the list, instead of [0:5] you can use [:5]
