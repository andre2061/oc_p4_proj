Chess tournament management
The aim of this application is to manage offline chess tournaments. You can create new tournaments, new players, add some players to a tournament, start and stop rounds, add results, and at the end, add new ELO rank. You can also view ranking, for a tournament or general, view all tournaments registered in the base, or the information of one tournament. You can at least modify elements of one player or one tournament, at any time.

How to execute the application ?
At first, you have to install python3 (I use the 3.9.6 version). You can find on the official site Python your version for Windows /Linux/ Mac.

Then you need to install a new environment for running the application, containing the packages included in the file requirement.txt .To do this, please follow the instructions below:

Create a virtual environment at the root of the project, using the command python -m venv env. Then, activate this environment :

Windows: venv\Scripts\activate.bat
Linux & Mac: source venv/Scripts/activate
After that, install the requirement.txt with using this command : pip install -r requirements.txt

Now you can start the application by running the main.py file: py main.py

Help for this application
To read some help about this application, you can use the command : py -m pydoc -b at the root of the project. It will open a browser page with the html help. it retrieves the docstrings present in the modules, describing the functioning of the different classes, methods and functions.

You can also retreive this documentation here : docstrings html

Flake8 report
You can find a flake8 report here : report

You can also do this command to make a new flake report, according the specifications :

flake8 --format html --htmldir flake8_rapport --max-line-length 119 main.py controllers models views

Presentation of this application
At first, when you start the application, you have a main menu :

Tournaments management
Players management
Reports
Exit
For interact with the application, you just have to enter your menu choice.

Tournaments management
In this part of the application, you can manage a tournament.

Add new tournament
in this part, you can configure a new tournament, with all options like name, place of tournament, date start and stop, control time (blitz, bullet or quick), number of even players, number of rounds, director description

View all tournaments
this way displays all tournaments known in the base.

Modify on tournament
This option allows you to modify elements of tournament :

add players

starting round

ending round and add results

view results of tournament

Return to main menu
Players management
In this part of the application, you can manage the players

add players
Allow you to add new players. You will be able to fill in the surname, first name, date of birth, gender and the ELO rating already known to the user. If this ranking does not exist (new player), by default the application will give a ranking of 1000.

view all players
this way displays all players known in the base.

Modify one player
This option allows you to modify elements of player :

name
first name
date of birth
sex
ELO rank
Return to main menu
Reports
This section can present you all statistics of tournaments and players (ELO rank, ranking by score or by name, information about tournament, rounds and matches...)

View all players - by rank
Display all players known in the base, sorted by ELO rank

View all players - by name
Display all players known in the base, sorted by surname

View list of all tournaments
Display a list of all tournaments known in the base.

View informations of one specific tournament
You can choose one tournament to view information about it.

View players - by score
Display the list of tournament's player, sorted by scores

View players - by name
Display the list of tournament's players, sorted by surname

View list of rounds and matches
Display all rounds and matches played in the tournament

View all other informations
Display all other information of the tournament, like place, control time, and director description.

Return main menu
Exit
