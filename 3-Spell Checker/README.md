MegaSoftWeird
Word processor, would like a spell checking functionality. Write a spell checker. Will provide a dictionary with correctly spelled words but for now, set up my own dictionary. Input will only contain letters and spaces. No punctuation or numbers. Capitalization.

Dictionary = This
Example Input                 | Example Output
"this"                        | "this"
"This is spelled crrectly"    | "This is spelled ~crrectly~"
"This is spellect crrectly"   | "This is ~spellect~ crrectly"
""                            | ""

Class - SpellChecker.new(String)
Dictionary with a list of words
Method - Check

----

sentence = SpellChecker.new("This is spelled crrectly")
sectence.check
"This is spelled ~crrectly~"

---
