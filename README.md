Magical Arena

Welcome to the Magical Arena! This program simulates battles between players in an arena until one of them loses all their health.

Problem Statement

In the Magical Arena, every player is defined by three attributes:

-> Health: The player's remaining health points. The player dies if their health reaches 0.

-> Strength: The player's defensive capability. It affects how much damage the player can resist.

-> Attack: The player's offensive capability. It determines how much damage the player deals to their opponent.

Players take turns attacking each other. Each attack involves rolling dice to determine the damage dealt and defended.

How to Run

1.Ensure you have Java installed: Make sure you have Java installed on your system.

2.Compile the code:javac MagicalArena.java

3.Run the program:java MagicalArena

Game Rules:

-> Each player attacks in turns.

-> The attacking player rolls a dice to determine the attack damage.

-> The defending player rolls a dice to determine the defense strength.

-> Attack damage = Attack value * Attacking dice roll

-> Defense strength = Strength value * Defending dice roll

-> Damage taken = Max(0, attack damage - defense strength)

-> The defender's health is reduced by the damage taken.

-> The game ends when one player's health reaches 0.

Example:-

Consider two players:

1.Player A: Health = 50, Strength = 5, Attack = 10

2.Player B: Health = 100, Strength = 10, Attack = 5

Here's how the game progresses:

-> Player A attacks Player B.

-> Player B defends against the attack.

-> Player B retaliates and attacks Player A.

-> Player A defends against the attack.

-> The game continues until one player's health reaches 0.

Unit Tests

Unit tests for the provided code are available in the MagicalArenaTest.java file. These tests cover various scenarios such as player attacks, health after attacks, attack damage calculation, and player health after no damage.

To run the unit tests:

-> javac MagicalArenaTest.java
   
   java MagicalArenaTest

This README file provides clear instructions on how to run the code, explains the problem statement, and outlines the game rules. It also mentions the unit tests and how to execute them.
