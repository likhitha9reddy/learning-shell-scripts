# learning-shell-scripts
Some of the codes are taken from the book, 'The Linux Command Line' by William Shotts (2nd Edition). The explanation and other things is based on what I have understood. This repos also contains other Shell scripts that I have written for some CTFs.

### Terminal Commands for creating the file

Usually, you can make a directory in the terminal, say bin, by typing:

`mkdir bin`

Then we will create the file called, 'file-name', where our BASH code will reside. Replace 'file-name' with your actual file name.

`vim ~/bin/file-name`

### Terminal Commands for changing permissions and executing the SHELL script.
After saving the file, if we were to execute it normally, we will get error as it is not a executable file. We have to make it an executable file. To do so, we use 'chmod' command.

`chmod 755 ~/bin/file-name
file-name`

Upon running the second command, the output of the file is displayed on the terminal. We can redirect this output to a browser, like Firefox. To do so, type the following commands:

`file-name > file-name.html
firefox file-name.html`

For more detailed explanation, you can visit my blog:
https://roadtofuturetech.wordpress.com/
