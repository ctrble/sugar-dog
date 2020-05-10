# Sugar Dog

Submarine zine game made for https://itch.io/jam/flyover-zine-jam

## Gather

- these rules
- paper (graph paper is recommended)
- writing utensil (pencil is recommended)
- at least 1 opponent (this game supports any number of additional players)

## Gameplay

### Start of the Game

Create the game map, the size of which is determined by number of players. The game is played on a grid. Label the horizontal axis with letters, and the vertical axis with numbers.

The base map size for a 2 player game is 6x6. Each additional player adds 2 to the width and height of the grid:
- 2 players: 6 x 6
- 3 players: 8 x 8
- 4 players: 10 x 10
- etc

Select a starting position on the map, mark it but do not reveal it to your opponent/s. Once all players have secretely noted their starting positions, play can begin.

The player who was most recently in a submarine goes first.

```
This player has decided to start in space C4, and is using an "s" to track the location
of their submarine. There are only 2 players in this example, so the grid is 6x6.

  +---+---+---+---+---+---+
6 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
5 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
4 |   |   | s |   |   |   |
  +---+---+---+---+---+---+
3 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
2 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
1 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
    A   B   C   D   E   F
```

### Playing the Game

Each player takes turns giving commands and determining results. Note your commands in the command log and mark your position (and any active torpedos or mines) on your map each turn. Movement is only to adjacent spaces, not diagonal spaces. It's advisable to track any contacts on the map, too. Refer to the Submarine Captain's Guide for more operational instructions.

```
This player now occupies space F4, and is using a "t" to track their active torpedo
and an "m" to track the location of a mine they placed. The player previously
identified a contact in F1, which they marked with "c".

  +---+---+---+---+---+---+
6 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
5 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
4 |   |   |   | m |   | s |
  +---+---+---+---+---+---+
3 |   |   |   |   |   |   |
  +---+---+---+---+---+---+
2 |   |   |   |   |   | t |
  +---+---+---+---+---+---+
1 |   |   |   |   |   | c |
  +---+---+---+---+---+---+
    A   B   C   D   E   F

    COMMAND LOG
    –––––––––––
1.  move to D4
2.  place mine in D4 (2 remaining)
3.  move to E4 (noted contact in F1)
4.  move to F4
5.  fire torpedo (moves to F3, then F2)
```

### How to Win

The last surviving submarine wins the game! If no submarines survive then the game ends in a draw.

## Submarine Captain's Guide

### Map

The map is how you track your submarine's position, and the positions of your mines and torpedos. You are advised to also track contacts on your map, but you are not required to do so.

### Command Log

As the Captain of your submarine it is your duty to keep accurate records of your commands each turn. Commands are most easily tracked when grouped by turn, some turns you may only move, but sometimes you will also need to track the positions of torpedos. It can be difficult to remember what happened previously if you don't keep an orderly Command Log.

### Submarine

Your submarine has powerful engines with stealth capabilities, and is equipped with sonar, torpedos, and mines. While your submarine is powerful, it is fragile. Do not let anything impact it or all aboard will perish.

#### Engines

Your submarine is capable of high speeds, but the engines can generate significant noise and reveal your position, unless you suppress all unnecessary noise by moving slowly and purposefully.

##### ACTION: Silent Running

- Either maintain your position or move 1 space (silently, do not announce contacts)

##### ACTION: Cruise

- Move 2 spaces (though you cannot move diagonally, you can move to the side and then over):
- As each space is entered, follow the same protocal:
  1. Announce a contact in the space
  2. Pause for contacts
      - If there is another contact in the same space, both contacts are destroyed
      - If there are no contacts, either move into the second space and check the protocal, or announce there are no further contacts
- If another contact is in the same space, a collision occurs and everything in that space is destroyed

#### Sonar

Your submarine has two kinds of sonars available: passive and active. Passive sonars pick up sounds in the vicinity, while active sonar generates a loud "ping" that returns echoes, revealing objects even if they are stationary.

##### ACTION: Active Sonar

- Announce a "ping" and subsequent contact/s
  - Announce your position first (as the source of the "ping"), then announce your mine and torpedo positions, if you have any
- Request responses
  - When responding, announce yourself, active mines, and active torpedos
- Always list the positions closest to the sonar source first

#### Torpedos

Torpedos are deadly missiles that destroy anything they impact with.

##### ACTION: Fire Torpedos

- Each turn, torpedos move 2 spaces in a straight line
- Once torpedos move off the map, they are lost to the void
- As each space is entered, follow the same protocal:
  1. Announce a contact in the space
  2. Pause for contacts
      - If there is another contact in the same space, both contacts are destroyed
      - If there are no contacts, either move into the second space and check the protocal, or announce there are no further contacts
- If a torpedo enters the same space as anything else:
  1. Announce an impact
  2. Everything in that space is destroyed

#### Mines

Mines are dangerous bombs that detonate when something strays into them. Each submarine carries a limited supply of 3 mines.

##### ACTION: Place Mine (if available)

- Place the mine at your current position (if you have mines available)
- Remove the mine from your inventory when it's placed
- If another contact moves into the space a mine is in:
  1. Announce an impact
  2. Everything in that space is destroyed

## FAQ

Can a submarine occupy the same space of another submarine or mine?
> Yes, if the submarine is silent running, meaning it's moving carefully and is potentially at a different depth, it avoids collisions with nearby objects.
