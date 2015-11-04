## cx_Freeze Sample Project
A very basic sample shows that how to convert a **Python** project into an **executable** for Windows by using cx_Freeze. 

####Versions
```Python:     Python 3.4```<br>
```cx_Freeze:  you can get it from here``` http://cx-freeze.sourceforge.net/

####The project contains multiple modules in packages. 
There's a trick for the packages: "```__init__.py```" need to be put in the package folders, otherwise cx_Freeze won't recognize the modules in the folder. 

####The sample also contains "setup.bat" file. 
If you got cx_Freeze installed and set up the right Python path for the PATH parameters in the Windows environment parameters, you can generate an executable for this Python project by simply running the "setup.bat" file.
