## Lab 01

- Name: Hayden Godwin
- Email: godwin.20@wright.edu

## Part 1 - GitHub Profile

1. [Hayden-G25 Profile](https://github.com/Hayden-G25)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |  Windows help command is used to learn how to use commands and locates commands. Linux/ Mac man command lets users view reference manuals of a command or utility used in the terminal |
| Get-Location | pwd    |  Both commands help the user figure out what directory they are currently working in for the appropriate terminals    |
| Get-ChildItem | ls    |  Lists the items(files and folder) within the directory they are in      |
| mkdir   | mkdir       |  Used to create new directories    |
| Set-Location | cd     |  Used to change the current working directory      |
| New-Item | touch      |  Used to create a new folder      |
| Move-Item | mv        |  Used to move a item to a different directory      |
| Copy-Item | cp        |  Used to make a copy of a file and move it to a new location     |
| Remove-Item | rm      |  Used to delete files and directories of the file system      |
| notepad.exe | vim     |  Used to enter text into a file      |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: 

### Navigating My OS on the Command Line

1. Create a directory named `DirA`:  New-Item -ItemType Directory -Path C:\Users\Username\Documents\PowershellExample\DirA

2. Create a directory named `Dir B`: New-Item -ItemType Directory -Path C:\Users\Username\Documents\PowershellExample\"Dir B"

3. Go into `DirA`: Set-Location C:\Users\Username\Documents\PowershellExample\DirA

4. Go into `Dir B` from `DirA`: Set-Location C:\Users\Username\Documents\PowershellExample\"Dir B"

5. Return to your user's home directory: Set-Location C:\Users\Username\Documents\PowershellExample

6. Create a file named `test.txt`: New-Item -Path C:\Users\Username\Documents\PowershellExample\test.txt -ItemType File

7. Move the file named `test.txt` into `DirA`: Move-Item -Path C:\Users\Username\Documents\PowershellExample\test.txt -Destination C:\Users\Username\Documents\PowershellExample\DirA

8. Contents of `test.txt`:
```
Hello World!
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item -Path C:\Users\Username\Documents\PowershellExample\DirA\test.txt -Destination C:\Users\Username\Documents\PowershellExample\DirA\copy.txt

10. View the contents of `DirA`: Set-Location C:\Users\Username\Documents\PowershellExample\DirA (one in that directory) Get-ChildItem

11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item -Path C:\Users\Username\Documents\PowershellExample\DirA\test.txt -Destination C:\Users\Username\Documents\PowershellExample\"Dir B"\fodder.txt

12. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item C:\Users\Username\Documents\PowershellExample\"Dir B"

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

"The man command is a built-in manual for using Linux commands. It allows users to view the reference manuals of a command or utility used in the terminal." https://phoenixnap.com/kb/linux-man#:~:text=The%20man%20command%20is%20a,examples%2C%20and%20other%20informative%20sections. helped me understand what man does in Linux / Mac

"Get-Help is a multipurpose command that helps you learn how to use commands once you find them." https://learn.microsoft.com/en-us/powershell/scripting/learn/ps101/02-help-system?view=powershell-7.4 Helped me understand what help does in Windows PowerShell

"Gets information about the current working location or a location stack." https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-location?view=powershell-7.4 Helped me understand what Get-Location command did in Windows

"It prints the path of the working directory, starting from the root." https://www.geeksforgeeks.org/pwd-command-in-linux-with-examples/ Helped me understand what pwd did in Linux/Mac

"Gets the items and child items in one or more specified locations" https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-childitem?view=powershell-7.4 Helped me understand what Get-childItems command did in Windows

"Creates a directory or subdirectory" https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/mkdir Helped me understand what mkdir command did in Windows

"Vim, short for Vi IMproved, is a highly configurable text editor built to enable efficient text editing." https://www.geeksforgeeks.org/getting-started-with-vim-editor-in-linux/ Helped me understand what vim command did in Linux

"The rm (remove) command in Linux is used to delete files and directories from the filesystem." https://www.geeksforgeeks.org/rm-command-linux-examples/ Helped me understand what rm command did in Linux

"The Copy-Item cmdlet copies an item from one location to another location in the same namespace." https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/copy-item?view=powershell-7.4 Helped me understand what Copy-Item command did in Windows.

"mkdir or make directory" https://tutorials.codebar.io/command-line/introduction/tutorial.html#:~:text=The%20cd%20command%20allows%20you,command%20is%20cd%20your%2Ddirectory%20. Helped me understand what mkdir command did in Linux

"touch or create files" https://tutorials.codebar.io/command-line/introduction/tutorial.html#:~:text=The%20cd%20command%20allows%20you,command%20is%20cd%20your%2Ddirectory%20. Helped me understand what touch command did in Linux

"mv or move item" https://tutorials.codebar.io/command-line/introduction/tutorial.html#:~:text=The%20cd%20command%20allows%20you,command%20is%20cd%20your%2Ddirectory%20. Helped me understand what mv command did in Linux

https://youtube.com/watch?v=mjEN9gMll20 Video about how to create a folder in PowerShell

https://www.youtube.com/watch?v=A9nAz9luths Video about how to delete a folder using PowerShell

"Using double quotes ( " ) to enclose the directory name" https://labex.io/tutorials/linux-how-to-create-a-directory-with-spaces-in-the-name-in-linux-417527 Learned how to create a directory with a space in the name

"Copy-Item "C:\Wabash\Logfiles\mar1604.log.txt" -Destination "C:\Presentation"" https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/copy-item?view=powershell-7.4 Learned how to copy a file to a specified or existing directory

"notepad.exe filename.txt" https://stackoverflow.com/questions/11045077/edit-a-text-file-on-the-console-using-powershell Learned how to add text to a text file in PowerShell

"Move-Item -Path C:\Temp\test.txt -Destination C:\Backup" https://www.thomasmaurer.ch/2023/06/how-to-move-files-with-powershell/ Learned how to move files in PowerShell

"New-Item -Path "c:\" -Name "logfiles" -ItemType "directory"" https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/new-item?view=powershell-7.4 Learned how to make a text file in a directory in PowerShell

"C:\> Set-Location -Path Q:\MyDir" https://stackoverflow.com/questions/41130310/change-directory-in-powershell Learned how to use Set-Location in PowerShell to change directories