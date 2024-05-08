# University of Arizona Hackathon 2024
*by Cougar Bellinger and Lindsey Davis*
---
## Prompt:
Design and develop an interactive word game. The game should include an intuitive GUI and should be both interesting and fun to play.

## Game concept
We came up with a game which lists a set of letters. The player then needs to come up with as many words as they can that contain any of those letters. The player will earn a certain amount of points for each valid word, and if they don't reach a certain threshold of points, they fail. However, if they do reach the threshold, they will then advance to the next level which presents less letters that are less common in words. This goes on until 3 rounds, and the player wins when they complete all of the rounds.

## Implementation
We created our game in python using the pygames library. We didn't get to implement all of the game functions we wanted, so our game is very barebones. However, it has a start screen, game state, and end screen which was our minimum goal. We weren't able to make all of the round states for the game, and the end state is always a losing scene. The player is presented with a list of letters, and for each word that they enter the game provides feedback if the word has already been entered, is not a word, or is a word. 


