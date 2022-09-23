# `In Shell's Heart`

### ***[Shell](https://www.tutorialspoint.com/unix/unix-what-is-shell.htm) is an environment in which we can run our commands, programs, and shell scripts. There are different flavors of a shell, just as there are different flavors of operating systems. Each flavor of the shell has its own set of recognized commands and functions.***

### ***Shell provides you with an interface to the Unix system. It gathers input from you and executes programs based on that input. When a program finishes executing, it displays that program's output*** ###

![Image](https://64.media.tumblr.com/5cae09ebfd5a9dc6558f844f76e2fa57/16f7d332cfb95b1b-a3/s1280x1920/afed90ab692086f167a48eb7fdfc8c3a3b0584d6.png)

---

***Executing each command per task can be sometimes messy and create 
a little bit of "disorder" if you are not used to it. Therefore you can create a script within a file, using Vi, Emacs, or other preferred editors that can execute multiple commands at once if you authorize it to be in charge of executing. The script has its own structure and syntax which I will show you step by step.***  

---
***At the begging of the script, you should always include the core element of "composing" a script.*** ↓  

```
-> #!/bin/bash
```
---
***From there you click "Enter" on your keyboard and start typing the first command on the second row and the other in the next row and so on. In this scenario, I will demonstrate by using the ["cd"](https://phoenixnap.com/kb/linux-cd-command) command, which for you that don't know it's the command to navigate and change the working directory. Also, the "phoenix" is an example, not a real code.*** ↓

```
-> cd /root/phoenix/
```
---
***Afterwards you have to save the content by using the save command. For example in Emacs it's [C-x C-s](https://mally.stanford.edu/~sr/computing/emacs.html). Then exit "Emacs" by C-x C-c and then code this first step to make our script effective.*** ↓

```
-> chmod u+x <Name of File>
```
***Type this afterward from where you are.*** ↓

```
-> ./<Name of File>
```
---
#### ***`If you have followed the steps correctly and chronologically then your command should be executed within milliseconds. Don't forget you can write more than 1 command in your script and make them effective simultaneously.`*** 

---

                                      So long! #Holbie
   ![Image](https://images.squarespace-cdn.com/content/v1/5a4bfe8bf09ca4228ceca3b7/1539139199598-ANH454IHZI1OKWONKRXY/logo.jpg?format=2500w)
