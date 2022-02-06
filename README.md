Here are the rules of Pig Latin:

For words beginning with a vowel, add "way" to the end. For Pig Latin, vowels are "a," "e," "i," "o," and "u." Don't treat "y" as a vowel. Examples: "away" becomes "awayway" and "okay" becomes "okayway."

For words beginning with one or more consonants, move all of the first consecutive consonants to the end and add "ay". Examples: "code" becomes "odecay" and "move" becomes "ovemay."

If the first consonants include "qu", move the "q" and the "u." Don't forget about words like "squeal" where "qu" doesn't come first! Examples: "quick" becomes "ickquay" while "squeal" becomes "quealsay."

Specs:

It should ingore empty strings

It should ignore punctuation and non alphabetical characters ($, %, !, eg)

It should recognize all vowels a, e, i, o, u. 

It should identify words that begin with a vowel

It should add 'way' to the end of words that begin with a vowel

It should recognize words that begin with a consonant

It should move consonants of words that begin with them to the end

It should add 'ay' to the end of words that begin with consonants

It should move 'q' and 'u' to the end and add 'ay'



Describe: pigLatin();

Test: Should not accept an empty string.
code: pigLatin(" ");
Expected Output: 0;

