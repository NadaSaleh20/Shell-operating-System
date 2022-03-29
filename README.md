# Shell-operating-System

 The shell must support the following internal commands:
1. cd <directory> - change the current default directory to <directory>.
If the <directory> argument is not present, report the current directory. 
If the directory does not exist an appropriate error should be reported. This
command should also change the PWD environment variable.

2. clr - clear the screen.
  
3. dir <directory> - list the contents of directory <directory>
4. environ - list all the environment strings
5. echo <comment> - display <comment> on the display followed by a new
line (multiple spaces/tabs may be reduced to a single space)
6. help - display the user manual using the more filter
7. pause - pause operation of the shell until 'Enter' is pressed
8. quit - quit the shell
9. The shell environment should
contain shell=<pathname>/myshell where <pathname>/myshell is
the full path for the shell executable (not a hardwired path back to your
directory, but the one from which it was executed)
