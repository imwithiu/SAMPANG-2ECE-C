# ECE-2112-PA-1

**Made by: Julius Miguel S. Mendizabal | 2ECE-C**

The content of this repository contains the Programming Assignment 1 for our course "Advance Computer Programming" this S.Y. 2025-2026. This project covers three python problems pertaining to Module 1 - Base Computing with Python.

# **1. Alphabet Soup Problem**

Create a function that takes a string and returns a string with its letters in alphabetical order.

The following functions and methods were used in this problem:

• `sorted()` - a built-in function that returns a new sorted list from the elements of any iterable (like a list, tuple, string, or dictionary), in this case, an input from the user. 

Example: `sorted("hello")` --> ['e', 'h', 'l', 'l', 'o']

• `"".join()` - a string method that joins elements of an iterable (like a list or tuple) into a single string, with a separator string placed between each element, in our problem however, the sorted list from the word needs to become one word again without spacing so we used no seperation in between ("").

Example: `"".join(['e', 'h', 'l', 'l', 'o'])` --> ehllo

This built-in function and method were combined in order to create a single defined function that sorts the letters of a word alphabetically;


```python
def alphabet_soup(word):
   return "".join(sorted(word))

print(alphabet_soup(input("Enter a word: ")))
```

# **2. Emoticon Problem**

Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.

The following functions and methods were used in this problem:

A dictionary data type was utilized in order to store the equivalents of each word to an emoticon;

```python
emoticons = {"smile" : ":)", "grin" : ":D", "sad" : ":((", "mad" : ">:(" }
```

In order to replace the word in the sentence, a for loop was used to find the word and reference it to its equivalent value in the dictionary before replacing it in the sentence;

```python
for word, symbol in emoticons.items():

   sentence = sentence.replace(word, symbol)
```

Combining them all, the final function for this problem is as follows;

```python
def emotify(sentence): 
    emoticons = {"smile" : ":)", "grin" : ":D", "sad" : ":((", "mad" : ">:(" }

    for word, symbol in emoticons.items():
        sentence = sentence.replace(word, symbol) 
    return sentence 

print(emotify(input("Enter a phrase or a sentence: ")))
```


# **3. Unpacking List Problem**

Unpack the list into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

The following functions and methods were used in this problem:

A sample list was given:
`list = [1, 2, 3, 4, 5, 6]`

Using manual slicing the corresponding values from the list were assigned to their appropriate variables and printed.

```python
first = list [0] # this assigns the value in the first index [0] of the list to the variable "first"

middle = list [1:-1] # [1:-1] means [start at [1] : then stop at [-1] but exclude its value], therefore assigning all the values in the middle of the list to the variable "middle"

last = list [-1] # this assigns the value in the last index [-1] of the list to the variable "last"

print("first:", first)
print("middle:", middle)
print("last:", last)
```

Thank you for reading! 

To see the main python program for Programming Assignment 1, click this link https://github.com/juliusmendizabal/ECE-2112-PA-1/blob/main/Programming%20Assignment%201.ipynb and download. Open on Jupyter Notebook, then run all cells.

#### **README file Version History:**

August 27, 2025 - Initial README output uploaded.

August 28, 2025 - Format in README content was updated.

September 2 & 6, 2025 - More format tweaks in README content.

September 23, 2025 - Updated few details + a README file Version History.
