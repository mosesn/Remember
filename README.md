#Remember
Remembers a string and when you saved it. Could be used to remember when you
first heard about a mindblowing idea.

##Installation
Change the remember file's permissions to be executable,
and add it to your path.  
Edit the SAVE_FILE line so that it points to the file you want to use to save
your strings.

##Usage
```
remember {STRING}
```  
If you call remember on a string for the first time, it will remember it.
If you call it on a string you have already remembered, it will tell you
when you remembered it.