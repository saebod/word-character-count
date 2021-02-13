#  word-character-count
word-character-count counts the number of characters in your word document.  The function takes to argument, the **filepath** and a **stopword**. A stopword is used for when it's supposed to stop counting character  such as **References**.

## usage
in this example i want to know the number of characters in my word document test.docx, where i want to know how many characters is in my document untill the word Stop-python, which i have put some random place in my document.
```
from  WordCharacter import Character_Count
without= Character_Count('test.docx')
print(without)
>> 8623
witht = Character_Count('test.docx','Stop-python')
print(witht)
>> 886
```


###End
