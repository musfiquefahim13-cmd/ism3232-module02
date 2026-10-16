# ISM3232 - Module 2: zsh Navigation and File Operations

## Commands Practiced

| Command | What it does |
|---|---|
| `pwd` | Prints the current working directory |
| `ls` | Lists visible files and folders |
| `ls -la` | Lists all files, including hidden files, in long format |
| `cd ..` | Moves up one directory level |
| `cd ~/ism3232` | Goes directly to the ISM3232 course folder |
| `cd module02_zsh/week2_lab` | Moves into the Week 2 lab folder |
| `mkdir week2_lab` | Creates a new folder named week2_lab |
| `tree -L 2` | Displays the folder structure two levels deep |
| `touch notes.txt` | Creates an empty file named notes.txt |
| `echo 'Week 2 navigation practice' > notes.txt` | Writes text into notes.txt |
| `cat notes.txt` | Displays the complete contents of notes.txt |
| `head -1 notes.txt` | Displays the first line of notes.txt |
| `cp notes.txt notes_backup.txt` | Creates a copy of notes.txt |
| `mv hello_week2.py week2_script.py` | Renames the Python file |
| `code week2_script.py` | Opens the Python file in VS Code |
| `python3 week2_script.py` | Runs the Python script using Python 3 |
| `code .` | Opens the current folder as a VS Code workspace |
| `rm notes_backup.txt` | Permanently deletes the backup file after the safety check |

## AI Use Statement

I used AI as a tutor to explain the steps and help format this command reference. I personally ran and verified every lab command myself.
## Week 3: Virtual Environments and .zshrc

This week I learned how to create and use a Python virtual environment.

- `python3 -m venv .venv` — creates a virtual environment.
- `source .venv/bin/activate` — activates the virtual environment.
- `deactivate` — exits the virtual environment.
- `which python3` — shows which Python is currently being used.
- `pip install pytest ruff` — installs packages in the virtual environment.
- `pip freeze > requirements.txt` — saves installed package versions.
- `.gitignore` — prevents `.venv/` and cache files from being tracked by Git.
- `source ~/.zshrc` — reloads shell aliases.
- `ll` — runs `ls -la`.
- `gs` — runs `git status`.
- `mkcd` — creates a folder and moves into it.
