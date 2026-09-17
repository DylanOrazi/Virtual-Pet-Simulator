Virtual Pet Simulator

Project Overview:
Virtual Pet Simulator is a C++ application where the user cares for a virtual pet by managing hunger, happiness, energy, and health. The project includes both a console version and a graphical SFML version.

Project Purpose:
The purpose of this project was to practice C++ programming, game logic, file handling, and graphical application development using SFML. The project started as a console application and was later upgraded into a graphical desktop app.

Tools Used:
- C++
- Visual Studio
- SFML
- Windows Console
- File handling
- Release executable build

Main Versions:
1. Console Version
2. SFML Graphical Version

Main Files:
- VirtualPetSimulator_Console_Final.cpp
- VirtualPetSimulatorSFML.cpp
- VirtualPetSimulator.exe
- README.txt

Executable Files:
The executable version is located in the Executable folder.

Required executable files:
- VirtualPetSimulator.exe
- sfml-graphics-3.dll
- sfml-window-3.dll
- sfml-system-3.dll

Main Features:
- Create and care for a virtual pet
- Pet types: Dog, Cat, Dragon, Robot
- Hunger, happiness, energy, health, and age stats
- Feed pet
- Play with pet
- Let pet sleep
- Take pet to vet
- Save game
- Load game
- Random events
- Mood messages
- Game-over condition
- Graphical buttons
- Stat bars
- Pet graphics
- Message panel
- Release executable version

Console Version:
The console version includes the full game logic with a text-based menu. Users can create a pet, choose a pet type, perform care actions, check pet status, save the game, and load a saved pet.

SFML Graphical Version:
The SFML version turns the pet simulator into a graphical desktop application. It includes a custom window, pet graphics, clickable buttons, colored stat bars, a message panel, and visual layout improvements.

Pet Stats:
- Hunger: lower is better
- Happiness: higher is better
- Energy: higher is better
- Health: higher is better
- Age: increases as actions are performed

Pet Actions:
- Feed: lowers hunger and slightly improves health and happiness
- Play: increases happiness but lowers energy and increases hunger
- Sleep: restores energy and health but increases hunger
- Vet: improves health but slightly lowers happiness and energy
- Save: saves current pet data to pet_save.txt
- Load: loads saved pet data from pet_save.txt
- New Pet: resets the pet
- Change Pet: cycles between Dog, Cat, Dragon, and Robot

Random Events:
Random events can occur after actions. Examples include:
- Pet finds a snack
- Pet gets bored
- Pet catches a cold
- Pet has a burst of energy
- Pet makes a mess
- Pet takes a quick nap

How to Run the Executable:
1. Open the Executable folder.
2. Make sure the .exe file and required SFML .dll files are in the same folder.
3. Double-click VirtualPetSimulator.exe.
4. Use the buttons to care for the pet.

Skills Demonstrated:
- C++ programming
- Functions
- Structs
- Conditional logic
- Loops
- Random events
- File input/output
- Save/load system
- SFML graphics
- Button click detection
- UI layout design
- Stat bar visualization
- Release build creation
- Executable packaging
- Debugging and testing

Project Value:
This project is valuable because it combines programming fundamentals with graphical application development. It shows how a console-based C++ project can be expanded into a more polished desktop application using SFML.