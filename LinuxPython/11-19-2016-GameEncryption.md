# Game Code Encryption

## Spectacularly well-written plotline

Brooks, a lead programmer at Fallout 5, gets word that an evil malicious hacker named "Crsn" is attempting to steal all the data and shut down all their servers. Brooks calls up his friend, Tristan, a top hacker who happens to be a lead programmer at Persona 6 to encrypt his data.

## Your Mission

Help Brooks and Tristan write a program to encrypt the valuable Fallout 5 files and protect them from Crsn. Write a function called `changeChar`, which will take in three parameters. The first parameter will pass in line of text. The second parameter will pass in an exsisting letter within the line of text to be replaced. The third parameter will pass in a letter to replace it. `changeChar` replaces all instances of a given letter with another letter in a line of text recursively.

## Parameters

`lineOfText` - the line of text which need certain letters to replace.

`charA` - the character you want to be replaced.

`charB` - the character you want `charA` to be replaced with.

## Return Value

The function returns a single string, `lineOfText` with all instances of `charA` replaced with `charB`

## Example function call

`changeChar('The Jr DevLeague Academy is awesome!!', 'e', 'o')` will return  `"Tho Jr DovLoaguo Acadomy is awosomo"`

## Important Hints

- Strings have indices too, not just lists
- You can slice both strings and lists at the beginning or end.
