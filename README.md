# CMD

NOTE: Tested on Window 8.1 with Python 3.5.2

Before running edit options_dir on the 10th line in the main.py to the directory that you have main.py at. (Remember to use \\ for single slashed like I did it.)

You can execute the program using 2 ways. The first one is to run it in the directory the file is located. So if you want to run and use the program from anywhere then you should use method 2:

> 1:
  In the command line run it using
  python main.py {filename} {new/open} {path doesn't work}

> 2:
  To run it anywhere you will need to make a batch file that links it and passes the args.
  Then you can add the folder with the batch file to environmental variables.
  You can later call the name of the .bat anywhere.
  So if editor.bat links with the main.py then you can call it:
  editor {arg1} {arg2}
  editor {filename} {new/open}


Read about it on https://eis3.github.io/
