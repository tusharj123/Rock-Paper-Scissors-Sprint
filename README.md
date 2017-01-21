# Rock-Paper-Scissors-Sprint
import random;
player = input("Enter your choice (rock/paper/scissors): ");
player = player.lower();
while (player != "rock" and player != "paper" and player != "scissors"):
	print(player);
	player = input("That choice is not valid. Enter your choice (rock/paper/scissors): ");
	player = player.lower();
