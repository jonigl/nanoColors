# nanoColors (Syntax highlight for nano)

**Here are some steps to help you out (for Mac users)**

1. Create a new directory in /usr/local/share/ called 'nano' like this:
```mkdir /usr/local/share/nano```
2. Now, using nano, make a nano resource file for your C syntax like this:
```nano /usr/local/share/nano/javascript.nanorc```
3. Now put your javascript.nanorc code highlighting in this file and save it. 
4. Save that file and now open your user’s nano resource file by typing:
```nano ~/.nanorc```
5. In this file, add a reference to the c.nanorc file you just made like this:
```include "/usr/local/share/nano/c.nanorc"```
6. Save your user resource file.
7. You done!
