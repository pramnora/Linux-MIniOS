# Linux-MIniOS
Linux MiniOS Operating System  

**File created**: *21st May 2026 00:10 AM GMT*  
**Last updated**: *21st May 2026 12:15 PM GMT*  

To be honest, I'm not exactly sure when I started using Linux MiniOS Standard version..; but, I'm sure, I've been using it for around a year, at least, now.  

I brought a *cheap* mini-PC box from off eBay...costing around £50.00. It is really low on memory 4 GB/and, too, SSD drive space...; so, this PC runs extremely 'slow'...!  

-(But, I thought it might be possible to upgrade memory, later on.)-  

-----

## MINI-OS INFO.

Apparently, MiniOS comes in 3 different versions...  

- MiniOS Standard  
- MiniOS Toolbox  
- MiniOS Ultra  

...I'm running the Standard version.  

**NOTE**: MiniOS can be run from a 'live' external USB disk...; as it doesn't demand too much system memory.     

-----

## HOW TO UPDATE AND UPGRADE 'ALL' SYSTEM PACKAGES BY USING THE TERMINAL COMMAND WINDOW  

The command to update and upgrade all system packages is...

sudo apt update  
sudo apt upgrade -y  

-----

## WEB BROWSER

MiniOS comes with Firefox web browser already installed.

Control key...  

[CTRL]+[T], Opens a new tab  
[CTRL]+[W], Closes the current tab  
[CTRL]+[U], Displays the underlying web page codes  

Function keys...  

[F11],Full screen  
[F12],Web page inspector  

-----

## HOW TO INSTALL SOFTWARE  

## Database  

- sudo apt install redis  

Load database...  

redis-cli  

Insert/retrieve data...    

set name "Jack"  
get name  

Exit Redis Database...  

exit  

## Editors

- sudo apt install emacs  
- sudo apt install gedit    
- sudo apt install vim  

## PROGRAMMING

### CLISP

- sudo apt install clisp  

...next, type: clisp...to get the CList/CommonLisp program up and running on screen.  

Type: [CTRL] + [Z] to exit.  

EXAMPLE CLisp program to add 2 numbers (uses Polish prefix notation).  

Here's a simple CLisp program one can try...  

(print (+ 1 2)) ; outputs: 3   

Here's how to define/and, run a function...  

(defun add(x y)(+ x y))   
(print (add 1 2)) ; output: 3    

-----

## HARDWARE

### SOUND FIX ISSUES

Sometimes, I've had problems with the sound...; which sounds really 'tinny' when output through the built-in computer box speakers.    

However, I learned it's possible to change this by choosing 'headphones'.  

Menu -> Multimedia -> Volume control -> Output devices -> Port -> headphones (unplugged)    

...then, the sound output is sent through the computer monitor built-in speakers, instead; which sounds so much 'clearer'.  

-----

## Links...

## Web Sites

Official web site page...  
- https://minios.dev/?lang=en     

### YouTube Videos...

MiniOS: The Ultimate Linux Toolkit OS...(channel: TechHeart)  
- https://www.youtube.com/watch?v=plF2_FhdZWg  

