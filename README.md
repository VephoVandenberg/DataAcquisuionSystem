# DataAcquisitionSystem

This is my final year diploma project. System gathers information from different parts of system, i.e. RAM, HDD and Network traffic.

# Used tools
Projects was written using C++ and Qt for a better overall performance. report csv files were constructed with Python, filterning output ot utils. Also app requires both versions of python 2.x and 3.x for volatility and python scripts correspondingly.

# Requirements
In order to have a proper work of the program. You have to clone [LiME](https://github.com/504ensicsLabs/LiME) and [Volatility](https://github.com/volatilityfoundation/volatility) to /opt/. You have to launch project from the project directory that means you should perform cd to projectPath. And launch the app out there ./build/UniversityProject.

# Ahtung
App doesn't work on Windows, yet. And [Volatility](https://github.com/volatilityfoundation/volatility) doesn't process dumps of some Linux kernels, so check that out before start.

# Further upgrades
- Achieve work of program on different platforms
- Maybe write your own system tools
