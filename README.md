# 🏃‍♂️ Hyundai Future Adventure Sample (Roblox)

This is a collection of Roblox game systems that includes 3 samples. Each sample is provided as an .rbxm file and can be run directly in Studio.  

🔗 [Play the actual game on Roblox](https://www.roblox.com/ko/games/13457104744/Hyundai-Future-Adventure-obby)

## 📚 Contents

- [1. 🎟️ Lobby Sample](#1-lobby-sample)  
- [2. ⚙️ Core loop Sample](#2-core-loop-sample)
- [3. 🕹️ Minigame Sample](#3-minigame-sample)  

---

## 1. Lobby Sample 
This sample demonstrates a lobby system using mouse hover detection.  
It includes lobby initialization, player enter/exit state checking, and reset functionality.

## 🚀 Key Features   
> - Lobby setup using `CollectionService` on both server and client  
> - Lobby class defined using Lua `metatable`  
> - Lobby state is managed and updated on the server

## 🏷️ File Structure  
ReplicatedStorage/  
└── LobbyManagerModule  
ServerScriptService/  
└── LobbyManageScript  
StarterPlayer/StarterPlayerScripts/  
└── LobbyControlScript  
Workspace/  
├── LobbyA  
└── LobbyB  

## 🎮 How To Use
1. Drag the `.rbxm` file into Roblox Studio and place the scripts in the appropriate services.  
2. Hover your mouse over one of the lobby parts in the Workspace.  
3. The lobby status will update and reflect the interaction on the server.

## 📷 Demo Image
![lobby_sample_gif](https://github.com/user-attachments/assets/b20b1ba5-0edd-4a3c-aafe-72abae6efa49)

---

## 2. Core loop Sample
This sample showcases a basic core game loop system, including intermission, player timer, checkpoint, and kill parts.

## 🚀 Key Features   
> - Implements OOP using modules and metatables
> - Uses RemoteEvent for client-server updates
> - Sets up interaction parts using CollectionService

## 🏷️ File Structure  
ReplicatedStorage/  
└── GameManager  
ServerScriptService  
└── MainSystemServer 
StarterGui  
└── SampleScreen  
StarterPlayer/StarterPlayerScripts/  
└── MainSystemLocal
Workspace  
└── TestParts & Models 

## 🎮 How To Use
1. Drag the .rbxm file into Roblox Studio and place it in ServerScriptService.
2. After the intermission, your goal is to reach the green part.
3. Touching the yellow part will activate a checkpoint.
4. If the player falls onto the red part, they will return to the last checkpoint.
5. Reaching the green part ends the game.

## 📷 Demo Image
![coreloop_sample_gif](https://github.com/user-attachments/assets/084771f2-437e-4d94-b419-a8b7c08c6b5b)

---

## 3. Minigame Sample  
This sample includes a basic minigame and an initialization system that handles different minigame types efficiently.

## 🚀 Key Features   
> - Sets up interaction parts using CollectionService
> - Uses metatable to unify the initialization process across various minigame types

## 🏷️ File Structure  
ReplicatedStorage/  
└── InteractionTriggerModule  
│ └── ServerInteractionModule    
│ │ └── InteractionSample  
ServerScriptService/  
└── ServerInteractionController  
StarterPlayer/StarterPlayerScripts/  
└── ClientInteractionController  
Workspace/  
└── InteractionPart  
└── Button  

## 🎮 How To Use
1. Drag the `.rbxm` file into Roblox Studio and place it in ServerScriptService.  
2. The minigame starts when a player touches the yellow part.  
3. Press the red button part to proceed with the minigame.  
4. Once the game conditions are met, the minigame ends automatically.  

## 📷 Demo Image
![minigame_sample_gif](https://github.com/user-attachments/assets/86ca2b43-668e-41d4-b2ff-f7624cbbbe02)
