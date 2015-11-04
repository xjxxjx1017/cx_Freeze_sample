## cx_Freeze Sample Project
A very basic sample shows that how to convert a Python project into an executable for Windows by using cx_Freeze. 

####The project contains multiple files in packages. 
There's a trick for the packages: __init__.py need to be put in the folder, otherwise cx_Freeze will go wrong. 

####The sample also contains "setup.bat" file. 
If you got cx_Freeze installed and set up the right Python path for the PATH parameters in the Windows system, you can generate an executable for this Python project by simply running the "setup.bat" file.
