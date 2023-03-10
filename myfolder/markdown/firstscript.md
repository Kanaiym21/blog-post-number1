# How to get started with bashsripting

 ## If you are reading this blog post you must be familiar with *HTML*, *CSS* and *Javascript*

 In this blog post you will get information how to get started the shell in the Bash environment.

 In order to get started with me you need to have a **linux system** or **WSL** in case if you use Windows. Once you have ubuntu or related linux environment installed we can finally start! Let's go!

 _________________________________________________________________________________________________________________________

 First, create a bash script using this command:

    nano ~/script.sh

>The "~" character represents your home directory, so full path is home/username/script.sh

Once you are inside of a blank file you can begin writing your code. 
Every shell script starts with 

    #!/bin/bash

You can create a new directory named *myfolder* :

    mkdir myfolder

In order to go to that directory simply write "cd" and the name of the directory that you just created:

    cd myfolder

Next, you can create a file using "touch" command:

    touch index.html

You have created a file **index.html** inside of a **myfolder** directory. Now you can create other directories as well:

    mkdir css js img markdown

If you want to create files inside of your created directories you can follow these:

>for example, in *css/style.css* **/** means that file *style.css* is inside of a *css* directory, that's why we are using slash to indicate the location of a file where we want to create a specific file.

    touch css/style.css
    touch js/page.js
    touch markdown/firstscript.md
    touch read.me

Now you can write any code using *echo* command or you can copy a file with ready code:

    echo "<h1> \"Hello, World! \" " >> myfolder/index.html

And finally **code .** command will create and open thses files in **Visual Studio Code.**

In order to run your code you need to make it executable using this:

    chmod +x ~/script.sh

To run the script you in your terminal just write this:

    ~/script.sh

## Thank you for reading my first blog post. 

All useful information about bash can be found [Here](https://www.howtogeek.com/261591/how-to-create-and-run-bash-shell-scripts-on-windows-10/).
