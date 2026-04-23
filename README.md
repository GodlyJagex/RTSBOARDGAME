# RTSBOARDGAME
RTS Board Game
### Game Setup
 Each player starts with a empty Resource pool to track their Gold/Wood/Stone, A Town Center with 20 durability and 10 population cap and each player starts with 5 empty building slots.
### Winning and Losing the game
 Players lose the game when their Town Center is destroyed.
 Players win the game when all other players Town Centers are destoyed
 
### Turn Structure
- Start of turn events happen
- Make three Actions
- Choose if and how you want to attack an opponent
- End Turn
   
### Buildings
  - Players may use actions and resources to build buildings in empty building slots.
  - Players may dismantle builds for an action to open up a building slot, at the cost of the resources spent to build the building.
  - Buildings can be attacked
  - Buildings are destoyed when their durability reaches 0.
- Bank:
  - Description: At the start of your turn produce 1 Gold
  - Cost: 2 stone, 1 wood, 1 gold
  - Durability: 4
- Lumber Yard
  - Description: At the start of your turn produce 1 Wood
  - Cost: 1 stone, 1 wood, 2 gold
  - Durability: 4
- Stone Mine
  - Description: At the start of your turn produce 1 Stone
  - Cost: 1 stone, 1 wood, 2 gold
  - Durability: 4
- Small House
  - Description: Increase your population cap by 1
  - Cost: 1 stone, 1 wood, 1 gold
  - Durability: 3
- Medium House
  - Description: Increase your population cap by 2
  - Cost: 2 stone, 2 wood, 2 gold
  - Durability: 6
- Large House
  - Description: Increase your population cap by 3
  - Cost: 3 stone, 3 wood, 3 gold
  - Durability: 9
- Barracks
  - Description: At the Start of your turn produce one Soldier. During your turn you may use an action to make a soldier.
  - Cost: 3 stone, 3 wood, 3 gold
  - Durability: 9
    
### Actions 
- Prodcuce a resource
- Build a building
- Produce a soldier
- Dismantle a building
- Attack an enemy building or townhall
- Repair a building by 5 Durability
  
### Attacking
 - After taking all three actions players may then decide if and how they want to attack another player.
 - If you choose to attack, you will choose how many soldiers you want to attack with and which player you are attacking and which building of theirs you are attacking, you may only choose to attack their town hall if they have an empty building slot. The defending player will then decide if they want to block with their soldiers and how many they want to block with.
 - EX. If Player A attacks Player D's Barracks with 5 soldiers and player D blocks with 3 of their 6 soldiers, each player loses 3 soldiers and Player D's Barracks loses 2 durability. 
