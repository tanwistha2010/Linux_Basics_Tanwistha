# Linux Basics Assignment


- Name: Tanwistha Guha
- Project: Linux Basics
- Environment: Ubuntu on Windows Subsystem for Linux (WSL)

## Objective
To learn and practice essential Linux commands for file management,
text processing, searching, downloading files, permissions,
environment variables, and archive handling.

## Tasks and Commands

### 1. Create a directory
Command: `mkdir test_dir`
Purpose: Creates a directory named test_dir.

### 2. Create a file
Command: `touch test_dir/example.txt`
Purpose: Creates an empty file.

### 3. Rename or move a file
Command: `mv test_dir/example.txt test_dir/renamed_example.txt`
Purpose: Renames the file.

### 4. Display file contents
Command: `cat /etc/passwd`
Purpose: Displays the contents of the passwd file.

### 5. Display the first five lines
Command: `head -n 5 /etc/passwd`
Purpose: Shows the first five lines.

### 6. Display the last five lines
Command: `tail -n 5 /etc/passwd`
Purpose: Shows the last five lines.

### 7. Search for a pattern
Command: `grep "root" /etc/passwd`
Purpose: Finds lines containing the word root.

### 8. Compress a directory
Command: `zip -r test_dir.zip test_dir`
Purpose: Creates a ZIP archive of test_dir.

### 9. Extract a ZIP archive
Command: `unzip test_dir.zip -d unzipped_dir`
Purpose: Extracts the archive into unzipped_dir.

### 10. Download a file
Command: `wget -O lotus.html https://en.wikipedia.org/wiki/Nelumbo_nucifera`
Purpose: Downloads the webpage and saves it as lotus.html.

### 11. Change file permissions
Commands:
`touch secure.txt`
`chmod 444 secure.txt`
Purpose: Makes secure.txt readable by the owner, group, and others,
without granting write or execute permissions.

### 12. Set and display an environment variable
Commands:
`export MY_VAR="Hello, Linux!"`
`echo "$MY_VAR"`
Purpose: Sets an environment variable and prints its value.

## Project Files
- test_dir/: Contains the renamed example file.
- test_dir.zip: Compressed archive.
- unzipped_dir/: Extracted archive.
- lotus.html: Downloaded webpage.
- secure.txt: Read-only file.
- screenshots/: Evidence of task execution.
- README.md: Assignment documentation.

## Conclusion
This assignment provided practical experience with basic Linux
commands, file operations, text utilities, downloading files,
permissions, environment variables, and ZIP archives.

## GitHub Repository
https://github.com/tanwistha2010/Linux_Basics_Tanwistha
