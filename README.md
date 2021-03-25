Opens a txt file named note-DD_MM_YY-hh:mm.txt in an editor (default is gedit) in a notes directory (default is /home/$USER/Documents/Notes).

Install instructions:
```
git clone https://github.com/sylvan-c/Notes
cd Notes
chmod +x notes
sudo ln -s /home/$USER/Notes/notes /usr/bin/notes 
```

Usage:
```
No options: Opens new note in specified editor
-h: Shows help message
-l: Lists all notes in notes directory
-r: Opens most recent note in specified editor
```
