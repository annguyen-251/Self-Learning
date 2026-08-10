# Day 1 — Variables & Print

## What I learned
- A variable stores a value under a name, e.g. robot_name = "R2-D2"
- Strings (text) go in quotes: "R2-D2"
- Numbers don't need quotes: battery_level = 95
- print() displays output, and you can pass multiple things separated by commas:
  print("Robot Name:", robot_name)

## Terminal / file navigation
- The terminal has a "current folder" — you have to `cd` into a folder before running a file inside it
- `cd "Practice Spot"` moves into that folder
- `python day1.py` runs the file, but only works if you're already in the same folder as it
- `pwd` shows what folder you're currently in — useful for debugging "file not found" errors

## Bug I hit
- Got "No such file or directory" because I was in the root folder, not Practice Spot
- Fixed by cd-ing into the right folder first

## git add, push, and pull
- cd into a folder before running files in it
-git add . / git commit save changes locally
-git push sends them to GitHub — but fails if GitHub has changes you don't have locally
-git pull (or git pull --no-rebase) merges those remote changes in first
-Sometimes pull opens an editor for a merge message — just save/close (or click Commit) to finish it