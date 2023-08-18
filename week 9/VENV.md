For those of you running the python debugger but running in to some issues pointing to a virtual environment, I recommend this:

In VS Code, go to open up Settings. This is under File | Preferences | Settings

Find the value python.venvPath 

Point to the directory that keeps your virtual environments that you created. 

![image](https://github.com/leonardf-git/it3038-2023/assets/97567564/d17ba08a-f369-442c-a006-de07e1637bd1)


This file will save automatically. 

Now, restart VS Code. 

If it asks you to pick a Python interpreter, click it and select the venv folder you put in above. All of your venvs should show up here. 

![](/screenshots/21-10-28-16-37-45.png)

You can return to this menu by clicking the Python version at the bottom of the VS Code window
![](/screenshots/21-10-28-16-38-18.png)

Now your debugger will use this instance of Python. 
