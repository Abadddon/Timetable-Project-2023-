I) Programme execution instructions

To use and correctly interact with the programme, the user has to execute the following instructions for handling the different code cells bellow :

Initialisation : THe user must sart by executing code cells 1, 2 and 3 to import all necessary python libraries and create all functions, classes and class objects.

Login : The user must execute code cell 4 for lounching the interactive timetable (this will open the first GUI window, the login window).

Programme reset : If the user desires to reset all timetables, they must execute cell 3 again. this will destroy previously created class objects and will create new ones.

Docstring acces : If the user desires to check any function or class docstring they can do so by executing cell 5. They will then be presented to a GUI window that will allow them to chose a function or
class thanks to a combox and then view it's docstring.

Doctest and unit test : In this program only one function returns a value and it is the only fonction (find_user_from_id) on which we can use doctest and unit test.
The user can test this function byexecuting code cell 6.

II) Instructions for graphical interface

Once the previous steps have been completed and the login GUI window has been openned, the user will have to navigate throught multiple GUI windows to allow him to modify the different timetables.

Login window : First GUI window. Here the user will have to select a user id from a combox. Once the id has been confirmed the user will access the next window.

Timetable selection window : Seconde window. The user can here choose a timetable thanks to a new combox. The timetable selection will vary depending on the user's clearance level 
(determined by their id and what type of user they are ex : teacher, student or admin). Once the timetable has been confirmed the user will access the next window.

Timetable window : Third window. The user can look at and interact with the timetable. Editing will be permited if the user has the correct cleareance level. Only the class timetables can be 
edited by pressing on the timeslot buttons. This will enable the user to access a new window. Room and teacher timetables will be modifyed automaticaly depending on class timetable modification.

Timeslot modification window : Fourth window. Ennables the user depending on his clearance level, to modify a class timeslot's information (teacherand room). Those modifications affect aswell teacher and 
room timetable timeslots (if affected by the previous change). The modified timeslots appear in red.
