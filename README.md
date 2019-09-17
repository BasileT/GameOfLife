# Projet-Python-Game-of-Life
Projet Python de 3A STI GoL - v 0.0 (17/09/2019)
(http://files.vhugot.com/Restricted/Python/PythonNotes.pdf)[http://files.vhugot.com/Restricted/Python/PythonNotes.pdf]
# Check
Monde ouvert (cf Snake)

# Todo

- class Bob
  - constructor
    - ID (int)
    - Energy (int)
    - Speed (float)
    - Mass (float)
    - Perception (int)
    - Memory (Dictionnaire : une clé pour point mémoire, une clé pour tableau de cellules)
  - methods
    - Move
    - Parthenogenesis
    - Reproduce
    - Fight
    - Eat
  
- class Cell
  - constructor
    - Coordinates (tuple)
    - Food (int)
    - Bob list (Bob)

- class Map
  - constructor
    - cells (Cell[|])
    - size (int)
  - methods
    - spawnFood
    - spawnBlobs
    
- class Game
  - constructor
    - map (Map)
    - bobs (Bob[])
    - ticks (int)
    - foodPerDay (int)
    - bobsAtBegin (int)
