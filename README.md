# Git-Bash-Cheat-Sheet

- CLI stands for Command line interface, examples of CLI's are command prompt, git bash, powershell, zsh (mac)

- dir: shows all available directories and files. Short for directory, this works in gitbash/command prompt/powershell
- ls: pretty much the same as dir, shows all available files and directories for the directory you are currently located in the CLI, this works in git bash & powershell does NOT work in command prompt
  - popular option is the `-a` option this will show hidden files as well
- cd: short for change directory this can be used to navigate between folders in the CLI, syntax is `cd name_of_folder`
  - if you do `cd ..` this will take you up or back (however it makes sense to you) a directory 
  - `cd ../..` will take you back two directories, you can chain as many of these as you want together 
  - `cd folder/sub_folder` <-- you can use this to jump multiple directories if you want, caveat you need to know where you're going, i.e. you can use dir or ls to see whats in the second folder, for now if you're new I recommend making one jump and then using dir or ls to see what is in that directory. 
- mkdir: creates a new folder, short for make directory, syntax is `mkdir folder_name` this will create a folder in your current directory you are located in the CLI 
- touch: will create, change, modify a new file, I recommend just using it to create files for now you can do that by `touch file_name`
- nano: is our CLI file editor, sort of like notepad for the CLI. you can initiate it by typing `touch file_name` 
  - From there you can use the file editor as you would expect 
  - Ctrl + C will save the file 
  - At the bottom you will see all the available commands the ^ == ctrl key, just for reference 
  - it will then prompt you to "save modified buffer?" Y or N 
  - then it will ask you for a name, the name of the file will be the default if you hit enter it will overwrite and save that file
  - if you give it a different name it will create a new file with the contents of you nano entry and leave the old file as is
  - if you make no changes and use Ctrl + C it will just exit and skip all of this
- echo can be used to write to the console, like `echo hello` will output `hello`
  - you can write & create files in one step by using `echo your message > file_name.txt` this will create a file name file_name and the contents of that file will be "your message"
- rm: short for remove, if you want to remove a file, make sure it is located in your working directory of you CLI and then type `rm file_name`
  - if you want to remove a directory its as easy as `rm dir_name` 
  - if you want to remove a directory that has files in it you can simply use `rm -r dir_name`
  - `rmdir dir_name` exists but doesn't have the -r flag so thats why I recommend using just rm, plus rm works on everything rmdir only works on deleting directories 
- if you hit the up arrow on you keyboard it will cycle through all of you previous commands, as far as I know this works in all CLIs 


#### Ping me if you have anymore questions, some other stuff I talked about was the transparency of the gitbash and setting the ctrl+shift+v to equal paste instead of shift+insert 
