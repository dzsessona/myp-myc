
     
                                                           
       _____ ___.__.______             _____ ___.__. ____  
      /     <   |  |\____ \   ______  /     <   |  |/ ___\ 
     |  Y Y  \___  ||  |_> > /_____/ |  Y Y  \___  \  \___ 
     |__|_|  / ____||   __/          |__|_|  / ____|\_____|
           \/\/     |__|                   \/\/          
           

**Keep track of your commands and directories without headaches.**

* [What is it](#what-is-it)
* [How does it work](#how-does-it-work)
       * [myc for commands](#myc-for-commands)
       * [myp for paths](#myp-for-paths)
* [Installattion](#installation)


## What is it

Have you ever found yourself in the situation of looking into the history of your bash for a particualr command that you 
can't remember? Or maybe searching the web for it while you are thinking "I ran this command a million times, and I can't ever remember it!"
*I am one of those people !* So I wrote these two little scripts that allow me to store and retrieve with a couple of keystrokes 
some very long commands (or particulary complicated ones), or very long paths that are hard to remember. Maybe someone else can
find it useful.  

## How does it work

Once installed, the script creates a file in your home which is nothing more and nothing less that a list of commands (or paths) 
and a description. You can add at any time a particular command that you like but is hard to remember, and then just re-call it 
running the script again. Easier to give an example than trying to explain it maybe, here is an example of myc and myp:

### myc for commands

### myp for paths

Suppose you have a very long folder, for example `/Users/dzsessona/this/is/a/very/long/path/containg/files/that/i/use/often` 
that contains some files that you use quite often and obviously I never remember. What you can do is give it a label and add it
to myp as follow:

```
myp -a /Users/dzsessona/this/is/a/very/long/path/containg/files/that/i/use/often "MOST USED"
```

Now you can simply type in your console `myp` and you get the list of your favourite folders. Press 3 and you will end up 
in your directory containing your most used files. (Note that in this example i previously added Downloads and Document).

![myp image](./README_IMAGES/myplaces.png)
