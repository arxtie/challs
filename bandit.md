## Bandit Levels 0-27

CAUTION: There are spoilers ahead for Overthewire.org's Bandit levels. 
No passwords are revealed, only the commands used to get the password.

### Level 0
To first access the game, you must log into bandit.labs.overthewire.org (port 2220) with the username of bandit0 and password bandit0.
```markdown
ssh bandit.labs.overthewire.org -p 2220 -l bandit0
```
Input the password bandit0 when prompted.
Note: this is mostly how you will be accessing all levels, to access progressing levels, change bandit0 to banditX (x = level number)

### Level 1
View the readme file in the home directory for the password of bandit1
```markdown
cat readme
```
The cat command will output the file's content (aka the password).

### Level 2
The file you must read is a - (dash) 
To overcome this obstacle, use ./-
```markdown
cat ./-
```
./ can be used as an escape character, this is why it worked instead of cat -

### Level 3
File is hidden inside the inhere directory.
```markdown
cd inhere
ls -a
cat readme
```
ls -a displayed the hidden file

### Level 4 - 27
in progress

