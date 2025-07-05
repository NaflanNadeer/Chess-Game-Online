# Online Multiplayer Chess

**Overview:**  
This is an online multiplayer chess game that supports unlimited players connecting from different machines and networks. It is built using Python 3.7, Pygame, and Python’s built-in `socket` module. The architecture follows a basic client-server model where the server handles connections and game management, while clients manage the user interface and gameplay.

---

## Requirements

- Python 3.x
- Pygame

---

## How to Run

To run the game, follow these steps:

1. Open the following files and update the server address:

   - `client.py`
   - `server.py`

2. Run `server.py` on a server or a host machine that allows incoming connections.

3. Start two or more instances of the game on different machines or networks to play chess online.

---

## Known Issues

- Checkmate is not detected; players must manually quit the game using the `Q` key when it ends.
- Rarely, a specific move may cause the game to crash.
- En Passant (pawn capture rule) is not implemented.
