# How do I find my terminal?
If you are on MacOS, open Spotlight Search (CMD + Space) and search for the terminal. If you are on any flavor of linux, just search for terminal or hunt through your applications folder for the "terminal" app. 

# What do I do now that I have it open?
The challenge with teaching anyone how to use the terminal is the rather large learning curve associated with it. The best way to become good at using the terminal is to practice, practice and then practice some more. 

For the purposes of these examples, type everything AFTER the dollar sign ($) into your terminal. The $ sign is just to signify that the following commands are entered into your terminal.

A couple must-know commands:
**pwd**: "Print Working Directory". This command prints your current position within your filesystem.
Example: `$pwd` -> `/Users/kushdesai/github/ultimate-hackathon-starting-guide/getting-started-terminal/linux_macos-terminal`
**cd**: Stands for "change directory". Used to navigate into folders
Example: `cd ../windows-terminal` -> no output, but I am not in the windows-terminal folder. `..` refers to moving back ("up") one directory
**ls**: "list". This command lists all the files present in the current folder.
Example: `ls` -> `README.md`, since this README is the only folder in the linux_macos-terminal folder. 
**touch**: Creates a file
Example: `touch thisisatest.txt` -> creates a file named thisisatest.txt in the current directory
**mkdir**: Makes a directory (folder)
Example: `mkdir this_is_a_folder` -> creates a folder named this_is_a_folder in the current directory. 
**rm**: "remove". This command is used to remove files and folders from the terminal. NOTE: Use this command with caution, since deleted files cannot be recovered easily. 
Example 1: `rm thisisatest.txt` -> this removes the text file you created with `touch` in the last example
Example 2: `rm -r this_is_a_folder` -> the `-r` flag means "recursive", and is necessary to delete folders. This command deletes the folder you created in a previous example. 

# This isn't enough for me, where do I learn more?
Glad you asked! Explaining the entire functionality of the terminal is beyond the scope of this guide. However, a helpful group over at MIT created a lecture series called the "missing semester of your CS education". [Lesson 1](https://missing.csail.mit.edu/2020/course-shell/) is a very good and thorough introduction on how to use the Bash shell. While your specific machine may use a different shell, the commands are interchangeable for the most part and most of the functionality changes are reserved for more advanced usage. Good luck!