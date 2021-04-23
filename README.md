# My2DUnityProject
Practicing Unity in 2D, experimenting with tilemaps and sidescrolling and whatever comes to mind until I come up with a concrete concept for a project to work on as portfolio piece.

# Branch management:
  I never want to work directly on the root branch (main). The main branch is where all completed and function work will end up, but to do so, components will first be merged into dev from their respective branches. Then, they will be merged into staging (essentially a copy of main) to ensure that merge proceeds smoothly. From there, main into staging should work easily. Dev and main may not always be the same (dev may be merged into multiple times before merging down the line into main), so the extra layer between staging and main helps to ensure the safety of main. 

  individual component branches
    ^
  dev                               workable layer 
  --------------------------------------------------------
    ^                       
  staging                           safety layer
  --------------------------------------------------------
    ^
  main                              buildable layer
