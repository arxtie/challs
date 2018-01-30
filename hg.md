## Hackergateway Web Category
CAUTION: There are spoilers ahead for Hackergateway's Web category challenges. 

For this category, we will sometimes be using a tool called [Fiddler](https://www.telerik.com/fiddler) made by Telerik.

This is not a write up for beginners, so you might want to learn how to use Fiddler or browser developer tools first. 

### Voices In My Head
```markdown
ssh bandit.labs.overthewire.org -p 2220 -l bandit0
```
Input the password bandit0 when prompted.
Note: this is mostly how you will be accessing all levels, to access progressing levels, change bandit0 to banditX (x = level number)

### Comfortably Numb
View the readme file in the home directory for the password of bandit1
```markdown
cat readme
```
The cat command will output the file's content (aka the password).
