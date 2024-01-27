# Command cheatsheet

- `cd <DIRECTORY_NAME>` - Changes the directory of where you are currently located
- `mkdir <DIRECTORY_NAME>` - Creates a new directory in the current directory
- `touch <FILENAME>` - Creates a new file in the current directory
- `vim <FILENAME>` - allows you edit a given file
    - Once your inside and editing the file use these commands
    - `i` - allows you to enter editing mode
    - `esc` - closes you out of editing mode
    - After editing
    - `:x` - saves the files changes and closes the file
    - `:q` - If there were no changes closes the file
    - `:Q!` - If there were changes but you just want to cancel and close the file
- `rm <FILENAME>` - removes a given file
- `rm -rf <DIRECTORY>` - removes a directory and all of its contents
- `ls` - Lists directories contents
- `ls -l` - Lists directories with the permissions displayed
- `mv <PATHTOFILE>` `<PATHTOWHERETOMOVE>` - moves a file from once place to another
- `cp <FILENAME> <NEWFILENAME>` - copies and pastes an existing file.


### More advanced commands
- `chown` - Changes ownership of a file or directory
- `chgrp` - Changes ownership group of a file or directory

### Notes
- `../` - Goes back one directory when used in conjunction with `cd`
- 

### Errors

#### References: [Terminal](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)