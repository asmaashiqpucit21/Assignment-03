# Assignment 03: -

### 1. Create a string variable with your name and print it.


```python
my_name = "Asma Ashiq"
print(my_name)
```

    Asma Ashiq
    

### 2. Define a multiline string that includes line breaks and print it.


```python
Multiline_string = """I am a student of Mphil GIS and RS.
And i am precitising python as a beginner.
So that in future i become expert in programming"""
print(Multiline_string)
```

    I am a student of Mphil GIS and RS.
    And i am precitising python as a beginner.
    So that in future i become expert in programming
    

### 3. Access the first character of a string.


```python
string = "Hello"
first_character = string[0]
print(first_character)
```

    H
    

### 4. Access the last character of a string.



```python
string = "Hello"
last_character = string[-1]
print(last_character)
```

    o
    

### 5. Access the second to the fifth character of a string.


```python
string = "hello"
second_to_fifth_character = string[1:5]
print(second_to_fifth_character)
```

     ello
    

### 6. Attempt to change a character within an existing string and explain the result.


```python
string = "My name is asma ashiq"
new_string = string[:11] + 's' + string[13:]

print(new_string)

```

    My name is sma ashiq


### 7. Slice a string to obtain the first 3 characters.


```python
string = "Hello"
First_three_characters = string[:3]
print(First_three_characters)
```

    Hel
    

### 8. Slice a string to obtain the last 4 characters.


```python
string = "asma ashiq"
Last_four_characters = string[-4:]
print(Last_four_characters)
```

    shiq
    

### 9. Slice a string to get every second character.


```python
string = "My name is Asma Ashiq"
every_second_character = string[1::2]
print(every_second_character)
```

    ynm sAm si

### 10. Reverse a string using slicing.


```python
string = "My name is asma ashiq"
reverse_a_string = string[::-1]
print(reverse_a_string)
```

    qihsa amsa si eman yM

### 11. Create two string variables and concatenate them.


```python
a = "Asma"
b = "Ashiq"
concatenate = a + b
print(concatenate)
```

    AsmaAshiq
    

### 12. Concatenate a string with a number (convert the number to a string first).


```python
num = 90
text = "The num is" + str(num)
print(text)
```

    The num is90
  



### 13. Generate a string that repeats "abc" 10 times.


```python
rep = "abc" * 10
print(rep)
```

    abcabcabcabcabcabcabcabcabcabc
    

### 14. Create a string containing a repeating pattern of your choice.


```python
string = "Asma"
rep_pattern = "Asma" * 40
print(rep_pattern)
```

    AsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsmaAsma
   
    

### 15. Convert a string to lowercase using the lower() method.


```python
string = "Asma Ashiq"
lowercase = str.lower(string)
print(lowercase)
```

    asma ashiq
    


### 16. Convert a string to uppercase using the upper() method.


```python
string = "I am a beginner of PYTHON LANGUAGE"
print(string)

```

    I am a beginner of PYTHON LANGUAGE
    


```python
uppercase = str.upper(string)

print(uppercase)
```

    I AM A BEGINNER OF PYTHON LANGUAGE
    

### 17. Remove leading and trailing whitespace from a string using the strip() method.
    


```python
string = "       i am very enthusiastic about learning python programming language         "
removing_whitespaces = str.strip(string)
print(removing_whitespaces)
```

   i am very enthusiastic about learning python programming language

    

### 18. Check if a string starts with a specific prefix using the startswith() method.

### Condition 01: -


```python
a = "ASMA ASHIQ"
prefix = "ASMA"
start = a.startswith(prefix)
print(start)
```

    True
    

### Condition 02: -


```python
a = "ASMA ASHIQ"
prefix = "ASHIQ"
start = a.startswith(prefix)
print(start)
```

    False
    

### 19. Split a string into a list of words using the split() method.


```python
string = "This is my third assignment of NN and AI"
splitted = string.split()
print(splitted)
```

    ['This', 'is', 'my', 'third', 'assignment', 'of', 'NN', 'and', 'AI']
    

### 20. Join a list of words into a single string using the join() method.


```python
words = "Asma Ashiq", "Mphil", "GIS", "and", "RS"
joined = " ".join(words)
print(joined)
```

    Asma Ashiq Mphil GIS and RS
    
