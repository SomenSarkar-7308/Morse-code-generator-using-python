# Morse-code-generator-using-python
Morse code generator
<br> author-Somen Sarkar

conversion_dict = {
    "a": ".-",
    "b": "-...",
    "c": "-.-.",
    "d": "-..",
    "e": ".",
    "f": "..-.",
    "g": ".-",
    "h": "....",
    "i": "..",
    "j": ".---",
    "k": "-.-",
    "l": ".-..",
    "m": "--",
    "n": "-.",
    "o": "---",
    "p": ".--.",
    "q": "--.-",
    "r": ".-.",
    "s": "...",
    "t": "-",
    "u": "..-",
    "v": "...-",
    "w": ".--",
    "x": "-..-",
    "y": "-.--",
    "z": "--..",
}
word = input("Enter a word: ")
length = len(word)
result = " ".join([conversion_dict.get(str(c).lower()) for c in word if str(c).lower() in conversion_dict.keys()])
print('\nConverted word: \n')
print(result)
