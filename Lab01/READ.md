## Lab 01

- Name: Nicholas Seas
- Email: seas.10@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [NSeas1's GitHub Profile](https://github.com/NSeas1)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    | 
| help    | man         | displays pages of useful commands       |
| Get-Location | pwd    |  shows the working directory you are in      |
| Get-ChildItem | ls    |  list folders and files in the directory      |
| mkdir   | mkdir       |  creates a new directory      |
| Set-Location | cd     |   changes the directory you are using     |
| New-Item | touch      |    creates a new file    |
| Move-Item | mv        |    moves/rename a file or directory    |
| Copy-Item | cp        |    copies data from file or directories    |
| Remove-Item | rm      |    deletes a file or directory    |
| notepad.exe | vim     |    brings up a text editor to edit files    |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: WSL

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: echo $HOME
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd ../"Dir B"
6. Return to your user's home directory: cd ~
7. Create a file named `test.txt`: touch test.txt
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA/
9. Contents of `test.txt`:
```
Hi world
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp DirA/test.txt DirA/copy.txt
11. View the contents of `DirA`: ls DirA
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp DirA/test.txt "Dir B/fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`:rm "Dir B/fodder.txt"
rm -r "Dir B"

## Citations
ChatGPT (OpenAI) assisted me with finding the Command Line commands (Part 2). I feed it a prompt of the commands and it described what each one did.
To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.