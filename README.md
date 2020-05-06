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

Each player adds 4 to the width and height of the grid:
- 2 players: 8 x 8
- 3 players: 12 x 12
- 4 players: 16 x 16
- etc

Select a starting position on the map, mark it but do not reveal it to your opponent/s. Once all players have secretely noted their starting positions, play can begin.

```
This player has decided to start in space C4, and is using an "s" to track the location
of their submarine. There are only 2 players in this example, so the grid is 8x8.

  +---+---+---+---+---+---+---+---+
8 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
7 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
6 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
5 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
4 |   |   | s |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
3 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
2 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
1 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
    A   B   C   D   E   F   G   H
```

### Playing the Game

Each player takes turns giving commands and determining results. Note your commands in the command log and mark your position (and any active torpedos or mines) on your map each turn. It's advisable to track any contacts on the map, too. Refer to the Submarine Captain's Guide for more operational instructions.

```
This player now occupies space F4, and is using a "t" to track their active torpedo
and an "m" to track the location of a mine they placed. The player previously
identified a contact in F8, which they marked with "c".

  +---+---+---+---+---+---+---+---+
8 |   |   |   |   |   | c |   |   |
  +---+---+---+---+---+---+---+---+
7 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
6 |   |   |   |   |   | t |   |   |
  +---+---+---+---+---+---+---+---+
5 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
4 |   |   |   | m |   | s |   |   |
  +---+---+---+---+---+---+---+---+
3 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
2 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
1 |   |   |   |   |   |   |   |   |
  +---+---+---+---+---+---+---+---+
    A   B   C   D   E   F   G   H

    COMMAND LOG
    –––––––––––
1.  move to D4
2.  place mine in D4 (1 remaining)
3.  move to E4 (noted contact in F8)
4.  move to F4
5.  fire torpedo (moves to F5, then F6)
```

### How to Win

The last surviving submarine wins the game! If no submarines survive then the game ends in a draw.

## Submarine Captain's Guide

### Command Log

As the captain of a submarine it is your duty to keep accurate records of your commands each turn.

### Submarine

Your submarine has powerful engines with stealth capabilities, and is equipped with sonar, torpedos, and mines.

#### Engines

##### ACTION: Silent Running

- move 1 space
- do not announce position
- do respond to active sonars

##### ACTION: Cruise

- move 2 spaces
- announce first space, then second space
- do respond to active sonars
- if entering the same space as another contact then both are destroyed

#### Sonar

- passive sonar detects loud contacts, such as fast moving submarines and torpedos
- active sonar detects all submarines, mines, and torpedos
  - except submarines in stealth mode
  - if you used the active sonar, you are revealed (even if previously in stealth mode)

##### ACTION: Active Sonar

- announce position/s
    - include yourself and any active torpedoes
    - announce yourself first, then announce mine and torpedo positions
    - list the positions closest to the sonar source first
- request responses
    - when responding, announce yourself and your active mines and torpedos
    - list the positions closest to the sonar source first

#### Torpedos

- each turn, move 2 spaces in a straight line
- announce first space, then second space
- do respond to active sonars
- if a torpedo enters the same space as a submarine or another contact
  - announce an impact
  - everything in that space is destroyed

##### ACTION: Fire Torpedos

- announce torpedo position
- torpedos move at 2 spaces per turn
- announce first space, then second space
- do respond to active sonars

#### Mines

- each submarine starts the game with 2 mines
- place a mine at a position
- do respond to active sonars
- if another contact moves into the space a mine is in
  - announce an impact
  - everything in that space is destroyed

##### ACTION: Place Mine (if available)

- remove 1 mine from inventory
- do not announce position
- mines do not move
- if another contact moves into the space a mine is in
    - announce an impact
    - everything in that space is destroyed
- do respond to active sonars

## FAQ

- can a submarine occupy the same space of another submarine or mine?
  - yes, if the submarine is silent running or in stealth mode, meaning it's moving carefully and potentially at a different depth, thus avoiding collisions with nearby objects
