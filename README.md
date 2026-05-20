# Portfolio-5-Strings

# Song Analyzer

### (I made this program because I enjoy listening to music and wanted to create something related to my favorite songs while 
### learning about strings in Python. The program analyzes a song title by checking its length, changing letter cases, 
### and searching for words inside the title. This helped me better understand string operations and manipulation in a more fun and personal way.)

### ( I named this program as MusicString Analyzer.)

```python
print("=== MusicString Analyzer ===")

print("Please include the artist name for proper credits and acknowledgment.")
song = input("Enter your favorite song title and artist (example: Seasons by Wave to Earth): ")
```

### (These are the string operations.)

### (I used upper() and lower() because I wanted to see how Python can change the appearance of text.
### Since music titles can have different capitalizations, this helps me understand how strings can be modified
### and displayed in different styles.)

```python
title_only = song.split(" by ")[0]

print("Song title in uppercase:", title_only.upper())
print("Song title in lowercase:", title_only.lower())
```

### (This is the length of string.)

### (I used len() because I wanted to know how many characters are in my favorite song title.
### This helped me understand that strings are made up of characters and that Python can count them automatically.
### I also removed the artist name and spaces from the count so only the song title itself is counted.)

```python
title_only = song.lower().split(" by ")[0]
print("Number of characters (excluding spaces and artist):", len(title_only.replace(" ", "")))
```

### (This part checks if a word exists.)

### (I used this because many song titles contain emotional words like “love”, because many songs have the word love in their titles.)
### I wanted to check if the word exists in the title while practicing searching inside strings using in.
### I also used lower() so the program can still find the word even if the user types uppercase or lowercase letters.)

```python
if "love" in song.lower():
    print("The word 'love' is in the title!")
else:
    print("The word 'love' is not in the title.")
```

### (This gets the first three letters.)

### (I used the first three letters because I wanted to practice string slicing.
### Three letters are enough to show how slicing works without making the output too long.
### It also feels like a short preview or abbreviation of the song title.)

```python
print("First three letters of the song title:", title_only[:3])
```
