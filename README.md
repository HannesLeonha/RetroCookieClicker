
![Logo](https://raw.githubusercontent.com/ToastyBoiiiii/Retro-Cookie-Clicker/master/textures/icon/logo.png)

A small clone of Cookie Clicker that i have made!  
Feel free to explore the project and look at my spaghetti code.

## Running the game

Execute the following commands (you have to have [poetry](https://python-poetry.org/docs/) installed):
`poetry install`, `poetry run python main.py`

## Building the game

Install the pyinstaller library and run this command in the console and replace PATH_TO_PROJECT with the path to the project:  
```pyinstaller --noconfirm --onefile --windowed --icon "PATH_TO_PROJECT/CookieClicker/textures/icon/icon.ico" --name "Retro Cookie Clicker" --add-data "PATH_TO_PROJECT/CookieClicker/textures;textures/" --add-data "PATH_TO_PROJECT/CookieClicker/sounds;sounds/" --add-data "PATH_TO_PROJECT/CookieClicker/classes;classes/" --add-data "PATH_TO_PROJECT/CookieClicker/main.py;." --add-data "PATH_TO_PROJECT/CookieClicker/utils.py;."  "PATH_TO_PROJECT/CookieClicker/main.py"```

