# Paid Mafia

is a simple mafia game where choosing number of players and after will be need to get the imposter, and the aim of this project is to control how many times a user can get free access to the game, and after a specific log numbers, access to the game will require payment.

![image](https://github.com/user-attachments/assets/6ba3f17d-62a8-4021-96de-1dc76c8b2e4b)



write now is works as full locally and the recommend arch to make it funcationlly with a server side is: 
the Game
│
├── Local user database
│   └── users.json
│
├── Machine identifier
│   └── MAC-derived ID
│
├── Free attempt counter
│   └── 2 attempts
│
├── License window
│   └── license input
│
└── License verification
    │
    ├── GitHub
    │   └── valid license list
    │
    └── License server/database
        ├── license
        ├── machine ID
        └── usage count
