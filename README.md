# CPP_CellularAutomata_pt2_BusyBlock
A C++ OpenGL Renderer Of A Hexagonal Cellular Automata. From AxialRiver I Included A Fade In Effect With Newly Alive Cells To Give More Depth. I Also Fixed The Indexing On Odd Row Indexes So Now Properly Picks Neighbors. Simple Ruleset Gave Very Interesting Live System That Looks To Grow Inside Itself Looking Like A City Block With Many Interconnecting Parts. 

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/5ea3d1df-95b7-4844-aa2e-315e4565293f" alt="Cornstarch <3" width="105" height="169">

This Project Has Allowed Me To Get Very In Depth With What Really Makes These Sorts Of Systems Alive And Accepting Of Stable States While Also Making Sure We Don't Have Lock Ups.

----------------------------------------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/bb109c9a-3be8-449b-9562-3cff6f815bee" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/bb109c9a-3be8-449b-9562-3cff6f815bee" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/bb109c9a-3be8-449b-9562-3cff6f815bee" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/bb109c9a-3be8-449b-9562-3cff6f815bee" alt="Cornstarch <3" width="55" height="49">


**The Breakdown:**

  This Program Works ON A GLSL Window Calling Upon OpenGL For Rendering.
  
  We Have Vertexes Represented With Hexagonal Cells In A Grid Pattern On The Screen. These Hexagonal Cells Are Represented In A 2D Array. Each Cell
  Holds Its Associated Vertexes In The Shared Buffer Where All Hexagons Lie As Well As A Alive Boolean State. Using This Alive State, We React Based Upon Our Neighbors. Either Becoming Alive, Or Dying Based Upon Our Neighboring Cells States And Predefined "Game Of Life" Rulesets. 
  
  Our Current Ruleset Allows For At Most 6 Connected Neighbors, Allowing Strong Links Between Cells But Also Unique Patterns As Using Death Sine Waves We Destabalize The Stable States Of These HoneyCombed Structures Causing Changes Throughout The Struct Which Is Cool To See. Likewise We Have A Fade-In Feature In Which Allows The Cells To Give Off A Pseudo Lifetime As Bright Cells Are Known To Be Older Than Newer Cells Which Start Off Darker.

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/66089837-1d29-4276-827c-45c3aeafbf4a" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/66089837-1d29-4276-827c-45c3aeafbf4a" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/66089837-1d29-4276-827c-45c3aeafbf4a" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/66089837-1d29-4276-827c-45c3aeafbf4a" alt="Cornstarch <3" width="55" height="49">

----------------------------------------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/57586bf2-f3f9-41a3-8445-a9921a687ccf" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/57586bf2-f3f9-41a3-8445-a9921a687ccf" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/57586bf2-f3f9-41a3-8445-a9921a687ccf" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/57586bf2-f3f9-41a3-8445-a9921a687ccf" alt="Cornstarch <3" width="55" height="49">

**Features:**

![trimmedBall-ezgif com-optimize (2)](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/1ad6647b-351b-4651-84b6-8888cf2c6ae3)

****Corrupt, But Shows Depth Well:****

![boxed200-ezgif com-video-to-gif-converter (1)](https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/5d3f919f-d470-4259-873d-3bddac37be2a)


<img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/838da4af-4131-48c8-82c2-7f6e9105c343" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/838da4af-4131-48c8-82c2-7f6e9105c343" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/838da4af-4131-48c8-82c2-7f6e9105c343" alt="Cornstarch <3" width="55" height="49"><img src="https://github.com/Kingerthanu/CPP_CellularAutomata_pt2_BusyBlock/assets/76754592/838da4af-4131-48c8-82c2-7f6e9105c343" alt="Cornstarch <3" width="55" height="49">
