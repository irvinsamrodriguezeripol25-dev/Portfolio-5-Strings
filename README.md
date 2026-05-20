# Portfolio-5-Strings

# Favorite Song Analyzer

### (I made this program because I enjoy listening to music and wanted to create something related to my favorite songs while learning about strings in Python.
### The program analyzes a song title by checking its length, changing letter cases, and searching for words inside the title. 
### This helped me better understand string operations and manipulation in a more fun and personal way.)

```python
song = input("Enter your favorite song title: ")
```

### (String operations.)

```python
print("Song title in uppercase:", song.upper())
print("Song title in lowercase:", song.lower())
```

### (Length of string.)

```python
print("Number of characters:", len(song))
```

### (Check if a word exists.)

```python
if "love" in song.lower():
    print("The word 'love' is in the title!")
else:
    print("The word 'love' is not in the title.")
```

### (First three letters.)

```python
print("First three letters:", song[:3])
```
