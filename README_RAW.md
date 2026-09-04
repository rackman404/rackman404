Raw file for obsidian editing


<details>
<summary>About Me</summary>
</details>


# About Me

## Introduction
4th Year Computer Engineering (Software Stream) student at TMU. Currently looking for a software internship/job.

### Links

| Game Development                                                                                                                                                | Art Work                                                                                                                                                                                           | DSA Practice                                                                                                                                                                               | Linkedin                                                                                                                                                                                                       | Contact Email            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| [![Itch.io](https://img.shields.io/badge/-Itch.io-blue?style=flat-square&logo=Itch.io&logoColor=white&link=https://rackman.itch.io/)](https://rackman.itch.io/) | [![Artstation Badge](https://img.shields.io/badge/-Artstation-blue?style=flat-square&logo=Artstation&logoColor=white&link=https://www.artstation.com/rackman)](https://www.artstation.com/rackman) | [![Leetcode Badge](https://img.shields.io/badge/-Leetcode-blue?style=flat-square&logo=Leetcode&logoColor=white&link=https://leetcode.com/u/rackman/)](https://leetcode.com/u/rackman/)<br> | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jacky-zhang404/)](https://www.linkedin.com/in/jacky-zhang404/) | Jacky.Zhang404@gmail.com |

## Skills and Toolsets

### Languages

Comfortable:

| ![C](https://img.shields.io/badge/-C-blue?style=flat-square&logo=c&logoColor=white) | ![Javascript/Typescript](https://img.shields.io/badge/-Javascript/Typescript-blue?style=flat-square&logo=Typescript&logoColor=white)<br> | ![c#](https://img.shields.io/badge/-C_Sharp-blue?style=flat-square&logo=.net&logoColor=white) | ![Python](https://img.shields.io/badge/-Python-blue?style=flat-square&logo=python&logoColor=white) | ![Java](https://img.shields.io/badge/-Java-blue?style=flat-square&logo=openjdk&logoColor=white)<br> |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |

Familiar/Learning:

| ![C++](https://img.shields.io/badge/-Matlab-blue?style=flat-square&logo=Matlab&logoColor=white) | ![VHDL](https://img.shields.io/badge/-VHDL-blue?style=flat-square&logo=&logoColor=white)<br> | ![assembly](https://img.shields.io/badge/-Assembly-blue?style=flat-square&logo=&logoColor=white)<br> | ![C++](https://img.shields.io/badge/-Cpp-blue?style=flat-square&logo=c%2B%2B&logoColor=white)<br> | ![HLSL](https://img.shields.io/badge/-HLSL-blue?style=flat-square&logo=hlsl&logoColor=white)<br> | ![Bash and Batch Scripting](https://img.shields.io/badge/-Bash_&_Batch_Scripting-blue?style=flat-square&logo=gnu-bash&logoColor=white)<br> | ![mySQL/OracleSQL](https://img.shields.io/badge/-mySQL/OracleSQL-blue?style=flat-square&logo=mysql&logoColor=white)<br> |
| ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |

### Web and Desktop Frameworks/Libraries

Web Frontend/Backend:

| ![React](https://img.shields.io/badge/-React-blue?style=flat-square&logo=react&logoColor=white)<br> | ![Node.js](https://img.shields.io/badge/-Node.js-blue?style=flat-square&logo=Node.js&logoColor=white) | ![Express.js](https://img.shields.io/badge/-Express.js-blue?style=flat-square&logo=Express&logoColor=white)<br> |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |

Desktop:

| ![Electron](https://img.shields.io/badge/-Electron-blue?style=flat-square&logo=Electron&logoColor=white) | ![Pyside](https://img.shields.io/badge/-Pyside-blue?style=flat-square&logo=Pyside&logoColor=white)<br> | ![Pyside](https://img.shields.io/badge/-JavaFX-blue?style=flat-square&logo=JavaFX&logoColor=white)<br> |
| -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |

### Testing & CI/CD

| ![JUnit](https://img.shields.io/badge/-JUnit_(Java)-blue?style=flat-square&logo=junit5&logoColor=white) | ![NUnit](https://img.shields.io/badge/-NUnit_(C_Sharp)-blue?style=flat-square&logo=Nunit&logoColor=white)<br> | ![Unittest](https://img.shields.io/badge/-Unittest_(Python)-blue?style=flat-square&logo=unittest&logoColor=white)<br> | ![Github Actions](https://img.shields.io/badge/-Github_Actions-blue?style=flat-square&logo=githubactions&logoColor=white) | ![Docker](https://img.shields.io/badge/-Docker-blue?style=flat-square&logo=Docker&logoColor=white) |
| ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |

# Project Highlights

For each category/subcategory projects are listed in order of quality/complexity

<details>
<summary>Personal Projects</summary>
</details>

## Personal Projects

### Music 

|               Browser View               |                   Focused View                   |
| :--------------------------------------: | :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828194159.png) | ![](_images/Pasted%20image%2020260828194141.png) |

[Desktop Music Player (Electron)](https://github.com/rackman404/Desktop-Music-Player)
- Languages: Typescript, C#
- Tech Stack: Electron, React (MUI), Node.js, .NET 
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
	

|                                                                Preview                                                                 |
| :------------------------------------------------------------------------------------------------------------------------------------: |
| <br><img width="800" height="450" alt="Image" src="https://github.com/user-attachments/assets/bef0aeb1-20ce-4fce-8a90-61367e1d7ef5" /> |

[MSR Parser CLI (Python)](https://github.com/rackman404/msr-parser-CLI)
- Tech Stack:
	- Languages: Python
	- Packaging: [PyInstaller](https://pyinstaller.org/en/stable/)
	- Code Quality/Testing: [Pylint](https://pylint.readthedocs.io/en/stable/), [Coverage](https://coverage.readthedocs.io/en/7.15.4/), [unittest](https://docs.python.org/3/library/unittest.html)  
	- Workflow Automation: [Github Actions](https://github.com/rackman404/msr-parser-CLI/actions)
- Basic CLI interface tool for automatically downloading/converting/tagging music OST from Arknights
- Can support a wide variety of user parameters using CLI arguments
- Basic formatted and styled graphical interface (loading bars, alignment, colours, etc..)
- Rudimentary CI/CD in the form of Github action workflow scripts which executes unit tests, runs linters/code coverage, and builds the CLI into a .exe automatically as a github release (using local batch files and actions)

### Games


|                                                   View from Northbound Platform                                                    |
| :--------------------------------------------------------------------------------------------------------------------------------: |
|                                          ![](_images/Pasted%20image%2020260828194040.png)                                          |
|                                                              Pan View                                                              |
| <img width="800" height="450" alt="Image" src="https://github.com/user-attachments/assets/7de30e7a-5133-4043-84d7-74e446d7ff9a" /> |

[PS1 Styled TTC Station Walking Simulator](https://github.com/rackman404/PS1-Walking-Sim-TTC-Dundas-Public)
- Languages: C#, HLSL
- Current stable public build can be played here: (LINK)
	- Note that WebGL build that can be played in browser differs slightly from the windows build (forced to use fallback shaders, no letterboxing, and other compromises due to WebGL limits)
- Tools/Engines: 
	- Game Engine: Unity
	- Art: Maya 3D (Modelling, Animations, Rigging), Substance Painter (Texturing)
- Basic walking simulator made as a testbed for graphics and character code to be reused in a couple future projects I have in mind
- Custom shaders taken [here](https://assetstore.unity.com/packages/vfx/shaders/psx-shader-kit) with modifications/extensions to HLSL source code as required:
	- reimplementation of lightmaps into Vertex Lit shaders
	- Increased vertex lights per mesh
- Additional HLSL shaders written from scratch as required (i.e wireframe shader)
- NOTE: I have not linked the actual repo here (this is a duplicate repo with only selected documentation and shader code included)
	- Not sure if I'm even allowed (some art assets almost certainly use trademarked TTC designs. I also plan on reusing most code in a later project) 
	- contact if you want to see the actual source code/art assets


|               Mid game screenshot                |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828193650.png) |

[Asteroid Dodging Game (Space Freighters)](https://github.com/rackman404/space-freighters)
- Languages: C#
- Tech Stack:
	- Game Engine: Unity
- Can be played [here](https://rackman.itch.io/space-freighters)
- Basic 3D ship obstacle dodging game
- Core gameplay loops involves surviving as long as possible
- Dynamically created levels using RNG based obstacle creation and clustering methods
- Destructible and modular ship (whereby destroyed ship parts slow down the ship)

|           Mid game screenshot            | Game Over                                |
| :--------------------------------------: | ---------------------------------------- |
| ![](_images/Pasted%20image%2020260904162402.png) | ![](_images/Pasted%20image%2020260904162339.png) |

ROR2 Themed Memory Game (React)
- Memory game (given N amount of cards, pick the one whose description matches item name)
- Basic frontend only react app, deployed using Vercel
- Can be played [here](https://memorygameror2.vercel.app/)

|                                                       Mid game screenshot                                                        |
| :------------------------------------------------------------------------------------------------------------------------------: |
|                                         ![](_images/Pasted%20image%2020260828201640.png)                                         |
|                                             Dynamic Terrain Generation (From Noise)                                              |
| <img width="800" height="450" alt="Image" src="https://github.com/user-attachments/assets/66584d83-8da2-4afe-8fa3-b2960d65ee5b"> |

[Top Down Vampire Survivors-Like Game](https://github.com/rackman404/Top-Down-Shooter-Game)
- Unfinished prototype
- Dynamic terrain generation written from scratch
- Tech Stack: Unity
- No link available to game, didn't go beyond prototyping

|  Daytime View (With the shader adjustments, appears to be night)  |
| :---------------------------------------------------------------: |
| ![Carrier Command 2](_images/Pasted%20image%2020260828193455.png) |


[Carrier Command 2 Permanent Night-time Shader Adjustments](https://github.com/rackman404/CC2-Night-Time-Shader-Mod)
- Steam Workshop link: https://steamcommunity.com/sharedfiles/filedetails/?id=3239591548
- Simple adjustments to various keywords and parameters in GLSL shader files that the Devs exposed
- Effects are that regardless of the actual in game time, it will always be night time visually within the game

<details>
<summary>Academic Projects</summary>
</details>

## Academic Projects
Note that some coursework lab repos aren't public. Will probably make them public after graduation.

### Software Course Projects
- COE692 Full stack Rug Storefront (Java)
	- A online rug storefront with a fully functional full stack (i.e user authentication, database, etc..)
	- Uses several architectural patterns such as microservices and MVC.
	- Project done in collaboration with a fellow student
	- Implemented using Java and basic HTML, served with Apache Tomcat, with Oracle SQL as the database system  
- CPS510 Database University Enrolments System (Python/SQL)
	- Simple end of course project, implements 
- COE528 JavaFX Bank Application (Java)
	- Basic JavaFX GUI and backend for simulating a rudimentary bank application in Java 
### Misc Coursework
- CPS188 Obesity Statistics Program (C)
	- Final project for CPS188, simple C program that parses a CSV file of Canadian obesity statistics and displays its graphically

### Low Level/Hardware Course Projects


<ins>COE538 Line Follower Robot (Assembly)</ins>
- Project consists of a prebuilt robot, with the goal of designing a assembly program that can allow it to navigate to the end of a maze by following black tape (using a photosensor onboard to detect) 
- Uses a state machine dispatcher to determine the next moves of the robot


|       Example Waveform (Instruction ADDI)        |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828200642.png) |

<ins>COE608 Semi-RISC CPU (VHDL)</ins>
- Designed and architected a basic RISC like CPU according [to these specs](https://www.ee.torontomu.ca/~courses/coe608/labs/CPU_Specification.pdf)
- Fully functional multi cycle datapath with 32-bit registers and 16 bit memory (256B program memory and 1KB data memory)
- Capable of reading a series of assembly instructions from a limited instruction set


|          Waveform (All OPCODE outputs)           |             Abstract Component View              |
| :----------------------------------------------: | :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828202341.png) | ![](_images/Pasted%20image%2020260828202440.png) |

<ins>COE328 16 Bit Arithmetic Logic Unit (ALU) (VHDL)</ins>
- Implemented a 16 bit ALU that can accept a given OPCODE for changing ALU mode and manipulates 8 bit inputs A and B to provide a 8 bit output result (split into 2x4 bit output)
- Able to interface with a Altera FPGA board to allow user input from switches and outputs to 7 Segment LCD displays

### MetRocketry Design Team Projects

|           Dashboard (Test Launch Data)           |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828193536.png) |

(2025-Current) [Tauri based Avionics Groundstation GUI](https://github.com/Ryerson-Rocketry/Avionics-Tauri-Groundstation-SRAD-GUI)
	- Made in collaboration with several MetRocketry members
	- Application accepts data from a radio receiver from Serial (which itself receives data from the rocket)
	- Tauri based desktop application with rust backend for CRUD operations and application management, Python Webserver backend subprocess for radio connection and data parsing/validation, and React frontend
	- Displays telemetry in the following format: 3D map with rocket position/flight path and trackball (Pitch/Roll/Yaw), 2D map, textual displays, graphs, and radio statuses
	- Addition features planned (Livestream integration from onboard camera)
	- Used in competition for IREC 2026 and likely IREC 2027 in the future


|       Dashboard (Test Launch Data)       |
| :--------------------------------------: |
| ![](_images/Pasted%20image%2020260828220507.png) |

(2024-2025) [Electron based Avionics Groundstation GUI](https://github.com/Ryerson-Rocketry/Groundstation-GUI)
	- Improved Groundstation GUI 
	- Same feature set as the Pyside based application
	- Used during IREC 2025

|           Dashboard (Test Launch Data)           |
| :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828203120.png) |

(2023-2024) Pyside based Avionics Groundstation GUI
- Simple desktop application using Pyside for the application framework and Python.
- Developed with guidance from a lead avionics member.
- Interfaces with a radio receiver via Serial.
- Parses and displays telemetry data via graphs, 2D map, and text displays
- Used during IREC 2024

<details>
<summary>Docs and Older Projects</summary>
</details>

## Docs

[Personal Leetcode Solutions + Basic DSA theory](https://github.com/rackman404/Leetcode-Personal-Solution-Documentation-Repo)
	- My approaches to some Leetcode questions I've done
	- Some patterns and personal notes on DSA as well
	
[MIT OCW Intro To C++](https://github.com/rackman404/MIT-OCW-Cpp-Problem-Sets)
	- My solutions and notes to some practice problem sets for C++


## Older Projects

|                   Music Player                   |                Ask Wikipedia API                 |
| :----------------------------------------------: | :----------------------------------------------: |
| ![](_images/Pasted%20image%2020260828213015.png) | ![](_images/Pasted%20image%2020260828213027.png) |
|                   OCR Scanner                    |                                                  |
| ![](_images/Pasted%20image%2020260828213054.png) |                                                  |


[Discord Bot (Python)](https://github.com/rackman404/Discord_Bot)
- Discord bot created using the official Discord API for Python
- Bot accepts various parameters and commands from a chat message to execute various functions
- Features include OCR scanner, Wikipedia search API, Music player, and various administrative roles (i.e chat monitoring -> remove message if profanity)

[FFmpeg-GUI (Pyside)](https://github.com/rackman404/FFmpeg-GUI)
- Basic wrapper for FFmpeg, written with Python with Pyside as the GUI
- User can select files and destinations from file explorer and perform file conversions using a FFmpeg side process 