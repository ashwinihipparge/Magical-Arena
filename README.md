# Magical-Arena

It defines two classes Player and MagicalArena for simulating a combat scenario between two players. Here's a brief overview of what each class does:

Player class: Represents a player in the magical arena. It has attributes for health, strength, and attack. The constructor initializes these attributes, and there are getter and setter methods to access and modify them.

MagicalArena class: Simulates the combat scenario between two players. It takes two Player objects as input and conducts the battle according to the rules specified in the problem statement. The fight() method initiates the battle, where players take turns attacking and defending until one player's health reaches zero.

Main class: This class contains the main() method, which serves as the entry point of the program. It prompts the user to input the attributes for both Player A and Player B, creates Player objects accordingly, initializes a MagicalArena object, and initiates the fight.

The combat simulation is implemented using random dice rolls for attacking and defending, with damage calculations based on the players' attributes.


->To run this code:
  Compile the Java file (Main.java).
  Execute the compiled class file (Main.class).
  This will initiate a fight between Player A and Player B in the Magical Arena, displaying the progress of the battle and announcing the winner at the end.
