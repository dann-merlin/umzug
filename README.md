# Umzug
Umzug - A command-line program to track what is in which move boxes written in python.

# Usage

## Add a new box
```
umzug add-box [box]
```
If no box name is specified, Umzug tries using numbers counting up from 1.

## Insert an item into a box
```
umzug insert item [box]
```

Inserts an item into a box. If no box is specified, Umzug tries to guess the correct box (either the last created or last used box, depending on which action was more recent).

## List boxes
```
umzug list [box ...]
```

Lists the specified boxes (all if none are specified) and their contents.

## Undo
*TODO*

Reverses the changes introduced by the last command. 
