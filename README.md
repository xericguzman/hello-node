# Hello Node!

Tradition in programming is that the first program you write with a new language is a program that simply logs out the message "Hello world."

We'll follow tradition in this assignment and write the Hello World program in Javascript. We'll then run this program using Node.js, a program that we'll run using the command line.

## Step 1: Install Node.js

#### On MacOS

**Install Homebrew**

On MacOS, first install Homebrew which is a package manager for command line programs. To do this, go to https://brew.sh/ and paste the command under 'Install Homebrew' into your command line.

**Use Homebrew to install Node.js**

Now that Homebrew is installed, type `brew install node` to install Node.js

#### On Windows with WSL2 (or Linux)

WSL2 is just Linux really which (assuming you're on Ubuntu or Debian) has a package manager installed by default (`apt`) that we can use to install Node.

Simply run, `sudo apt instsall nodejs npm`

#### On Windows with Git Bash

Sadly, there is no available package manager for Git Bash on Windows. The good news is you can still install Node. Go [here](https://nodejs.org/en/download/), then download and run the Windows installer.

## Step 2: Writing Hello World

Now, fork this repository and clone it to your computer. Open up the folder in VSCode and create a javascript file called `main.js`. Write a line of code that logs out "hello world".

Finally, lets run the program. In the command line, navigate to the directory containing `main.js`. Run it with the command `node main.js`. If you see "hello world" logged out in the terminal, you've succeeded! 

## Step 3: Mega Hello World

Now, see if you can log out the following text (you'll need multiple `console.log` statements).
```
HH   HH        lll lll                                  lll      dd !!! 
HH   HH   eee  lll lll  oooo   ww      ww  oooo  rr rr  lll      dd !!! 
HHHHHHH ee   e lll lll oo  oo  ww      ww oo  oo rrr  r lll  dddddd !!! 
HH   HH eeeee  lll lll oo  oo   ww ww ww  oo  oo rr     lll dd   dd     
HH   HH  eeeee lll lll  oooo     ww  ww    oooo  rr     lll  dddddd !!!                                                                         
```

## Stretch Goals

Print out additional big text of your choice, feel free to use https://www.messletters.com/en/big-text/ for help. 
