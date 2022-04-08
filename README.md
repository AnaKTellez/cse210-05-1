Snake Collide
Snake Collide is a spinoff of the classic game that we all used to play on our cellphones. You play this game on a simulated terminal, with a textual interface. The difference is that this is a two person game where one tries to avoid hitting the other snake while trying to get the other player to run into their snake.

Getting Started
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.

python3 -m pip install raylib
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.```

py snake

You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure

---

cse210-05 (project root folder)
+-- Cycle (source code for game)
+-- game (specific classes)
+--casting (cast folder)
+--actor.py (actor class)
+--snake.py (snake class)
+--cast.py (cast class)
+--directing (directing folder)
+--director.py (director class)
+--scripting (scripting folder)
+--action.py (action class)
+--control_actors_action.py (control_actors_action class)  
 +--draw_actors_action.py (draw_actors_action class)
+--handle_collisions_action.py (handle_collisions_action class)
+--move_actors_action.py (move_actors_action class)
+--script.py (script class)
+--services (services folder)
+--keyboard_services.py (Keyboard class)
+--video_service.py (video class)
+--shared (shared folder)
+--color.py (color class)
+--point.py (point class)
+-- **main**.py (program entry point)
+-- README.md (general info)

## Required Technologies

---

- Python 3.8.0
- Raylib Python CFFI 3.7

Authors:
-Ana Tellez (tel21003@byui.edu)
