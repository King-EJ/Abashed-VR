# Abashed-VR
VR mod for Abashed - GOG tested

<img width="1024" height="1024" alt="_Image_sagya5sagya5sagy" src="https://github.com/user-attachments/assets/9f90dedc-0a41-4ffc-9b99-702eaf40bd3c" />


unzip to game folder, only tested with virtual desktop XR,

HOW IT WORKS
 * Play: you stand at the game camera (moved closer to the scene by config MoveCloser) and look around with your head. The game's flat
   camera draws only the HUD (faster); the HUD floats in front of you, its black parts see-through.
 * Menus (the game's Menu input mode, pause, time stopped): the game's picture on a screen in front of you.
 * Dialogue / notes (Modal mode): the world stays, the HUD floats.
 * The VR controllers are a GAMEPAD for the game (so its own button icons and menu navigation apply).

CONTROLS
-
 Left stick ........ left stick (move)  
 
 Right stick ..... left / right = right stick, UP / DOWN = zoom your view forward / back
 
 A ................. South (A / Cross) 
 
 B ............... East (B / Circle)
 
 X ................. West (X / Square) 
 
 Y ............... Start (pause
 
 Left grip + Y ..... Select  
 
 Left grip alone ... LB 
 
 Right grip ... 
 
 Left trigger ...... LT 
 
 Right trigger ... RT
 
 Stick clicks ...... L3 / R3 (not together)
 
 Both stick clicks . re-centre the view;  hold both 1.2 s = VR settings menu (stick up/down choose, left/right change, A toggle, B close)

  NEW swap X and B ([Controls] SwapXB, VR menu)

IMPORTANT FOR THIS FIRST VERSION
 The mod sends gamepad input to the game as raw Input System events. The log says whether that works:
   "Virtual gamepad event layout 0: OK ..."   and   "Virtual gamepad check: left stick the game sees ..."
 If the game does not react to the controllers, send the log - it shows what the Input System read back.

 Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
