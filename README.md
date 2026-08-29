## Epic Readme

TABLE OF CONTENTS HERE

# About
---

### Introduction


### Other Links
- [Itch.io](https://rackman.itch.io/)
- [Artstation](https://www.artstation.com/rackman)
- [Leetcode](https://leetcode.com/u/rackman/)

### Social Links
- [Linkedin](https://www.linkedin.com/in/jacky-zhang404/)

---
# Skills
---




# Projects
---
For each category (and subcategory if applicable), projects are listed in order of complexity (i.e projects shown first in a category required more work/concepts to implement)

# Personal Projects
---
### Music 

|               Browser View               |                   Focused View                   |
| :--------------------------------------: | :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828194159.png) | ![](_images/Pasted%20image%2020260828194141.png) |
[Desktop Music Player (Electron)](https://github.com/rackman404/Desktop-Music-Player)
- Languages: Typescript, C#
- Tech Stack: Electron, React, Node.js, .NET
	- Electron as the Application framework with React for frontend and a standalone Node.js process in the backend. Uses a custom protocol for interprocess communication (IPC) between both sides.
- Main Features:
	- Standard music player functionality (Read files from disk, show metadata, plays them, etc..)
	- Live synced lyrics support (from either local .LRC files or retrieved from a online open source lyric API)
	- Live lyric translations from non English -> English (using external API service)
	- Automatic romanization into Hokkien, Mandarin, and Cantonese if supplied with supported open source dictionary file
- Secondary Features:
	- Rudimentary FFmpeg wrapper for performing audio file conversions or changing music file metadata
	- Live Discord presence (will display current song name/artist in Discord profile)
		- Done using a .NET side binary that is loaded and run as subprocess which hooks the user's currently running Discord desktop application if running
	


|                                                           GIF of it running                                                            |      Sample view (Downloading file)      |
| :------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------: |
| <br><img width="800" height="450" alt="Image" src="https://github.com/user-attachments/assets/bef0aeb1-20ce-4fce-8a90-61367e1d7ef5" /> | ![](_images/Pasted%20image%2020260828213842.png) |
- MSR Parser CLI (Python)
	- Tech Stack:
		- Languages: Python
		- Code Quality/Testing: [Pylint](https://pylint.readthedocs.io/en/stable/), [Coverage](https://coverage.readthedocs.io/en/7.15.4/), [unittest](https://docs.python.org/3/library/unittest.html)  
	- Basic CLI interface tool for automatically downloading/converting/tagging music OST from Arknights
	- Can support a wide variety of user parameters using CLI arguments
	- Basic formatted graphical interface in the CLI
	- Rudimentary CI/CD in the form of Github action workflow scripts which executes unit tests, runs linters/code coverage analysers, and builds the CLI into a .exe automatically

### Games


|          View from Northbound Platform           |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828194040.png) |
- PS1 Styled TTC Station Walking Simulator
	- Languages: C#, HLSL (Custom Shaders)
	- Tech Stack: 
		- Game Engine: Unity
		- Art Creation: Maya 3D (Modelling, Animations, Rigging), Substance Painter (Texturing)
	- Current stable public build can be played here: (LINK)
	- Basic walking simulator made as a testbed for graphics and character code to be reused in a couple future projects I have in mind
	- Custom HLSL shaders taken [here](https://assetstore.unity.com/packages/vfx/shaders/psx-shader-kit) with modifications/extensions to HLSL shaders as required:
		- reimplementation of lightmaps into Vertex Lit shaders
		- Increased vertex lights per mesh
	- Additional HLSL shaders written from scratch as required (i.e wireframe shader)
	- NOTE: I have not linked the actual repo here (this is a duplicate repo with only selected documentation included)
		- Not sure if I'm even allowed (some art assets almost certainly use trademarked TTC designs. I also plan on reusing most code in a later project) 
		- contact me if you want to see the actual source code/art assets i guess


|               Mid game screenshot                |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828193650.png) |
- [Asteroid Dodging Game (Space Freighters)](https://github.com/rackman404/space-freighters)
	- Languages: C#
	- Tech Stack:
		- Game Engine: Unity
	- Can be played here: (LINK)
	- Basic 3D ship obstacle dodging game
	- Core gameplay loops involves surviving as long as possible
	- Dynamically created levels using RNG based obstacle creation and clustering methods
	- Destructible and modular ship (whereby destroyed ship parts slow down the ship)

- ROR2 Themed Memory Game (React)
	-  Can be played here: (LINK)

![](_images/Pasted%20image%2020260828201640.png)
- [Top Down Vampire Survivors-Like Game](https://github.com/rackman404/Top-Down-Shooter-Game)
	- Unfinished and abandoned but placed in this category cause im quite proud of the dynamic terrain generator I wrote
	- Tech Stack: Unity
	- No link available to game, didn't go beyond prototyping

![Carrier Command 2](_images/Pasted%20image%2020260828193455.png)
- [Carrier Command 2 Permanent Night-time Shader Adjustments](https://github.com/rackman404/CC2-Night-Time-Shader-Mod)
	- Steam Workshop link: https://steamcommunity.com/sharedfiles/filedetails/?id=3239591548
	- Simple adjustments to various keywords and parameters in GLSL shader files that the Devs exposed
	- Effects are that regardless of the actual in game time, it will always be night time visually within the game


# Uni Projects
---
Note that some coursework lab repos aren't public (to prevent plagurism). Will probably make them public after graduation.

### Software Coursework
- COE528 JavaFX Bank Application (Java)
	- Basic JavaFX GUI and backend for simulating a rudimentary bank application in Java 
- COE692 Full stack Rug Storefront (Java)
	- Project done in collaboration with a fellow student
	- A online rug store with a fully functional full stack (i.e user authentication, database, etc..)
	- Implemented using Java and basic HTML, uses Apache Tomcat
- CPS510 Database University Enrolments System (Python/SQL)
	- Simple 
- COE318 Java OOP Assignments (Java)
	- General Object Oriented Programming Labs done in Java for the course
	- Will make this repo public after i graduate probably

### Misc Coursework
- CPS188 Obesity Statistics Program (C)
	- Final project
- COE628 Labs
	- General Operating Systems Lab work done for the course
	- Will make this repo public after i graduate probably

### Low level/Hardware Coursework


<ins>COE538 Line Follower Robot (Assembly)</ins>
- R
- 


![](_images/Pasted%20image%2020260828200642.png)
<ins>COE608 Basic CPU (Assembly)</ins>
- 

|                     Waveform                     |                Abstract ALU View                 |
| :----------------------------------------------: | :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828202341.png) | ![](_images/Pasted%20image%2020260828202440.png) |
	<ins>COE328 16 Bit Arithmetic Logic Unit (ALU) (VHDL)</ins>
- Implemented a 16 bit ALU that can accept a given OPCODE for changing ALU mode and manipulates 8 bit inputs A and B to provide a 8 bit output result (split into 2x4 bit output)
- Able to interface with a Altera FPGA board for 
	- 

### Electrical Coursework
<ins>ELE532 Labs</ins>
- General Lab work done for the course
- Will make this repo public after i graduate probably


### University Design Team Projects

|           Dashboard (Test Launch Data)           |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828193536.png) |
(2025-2026) [Tauri based Avionics Groundstation GUI](https://github.com/Ryerson-Rocketry/Avionics-Tauri-Groundstation-SRAD-GUI)
	- 


|       Dashboard (Test Launch Data)       |
| :--------------------------------------: |
| ![](_images/Pasted%20image%2020260828220507.png) |
(2024-2025) [Electron based Avionics Groundstation GUI](https://github.com/Ryerson-Rocketry/Groundstation-GUI)
	- Simple desktop application using Pyside for the application framework and Python.
	- Interfaces with a radio receiver via Serial
	- Parses and displays telemetry data via graphs, 2D map, and text displays


|           Dashboard (Test Launch Data)           |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828203120.png) |

(2023-2024) Pyside based Avionics Groundstation GUI
- Simple desktop application using Pyside for the application framework and Python.
- Developed with guidance from a lead avionics member in the team
- Interfaces with a radio receiver via Serial
- Parses and displays telemetry data via graphs, 2D map, and text displays



# Documentations
---
- Personal Leetcode Solutions + Basic DSA theory
	- My approaches to some Leetcode questions I've done
	- Some patterns and personal notes on DSA as well

# Misc
---
- MIT OCW C Basics
	- My solutions to the problem set for a C course

# Abandoned/Poorly Done Projects
---
Projects that were abandoned from time constraints or cause they were the first projects i've done


|               Music Player               |            Ask Wikipedia API             |
| :--------------------------------------: | :--------------------------------------: |
| ![](_images/Pasted%20image%2020260828213015.png) | ![](_images/Pasted%20image%2020260828213027.png) |
|               OCR Scanner                |                                          |
| ![](_images/Pasted%20image%2020260828213054.png) |                                          |
- [Discord Bot (Python)](https://github.com/rackman404/Discord_Bot)
	- 


- [FFmpeg-GUI (Pyside)](https://github.com/rackman404/FFmpeg-GUI)
	- Extremely basic wrapper for FFmpeg (Not even joking, basically just allows for converting by )

