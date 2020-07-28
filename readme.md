# Jetpack Joyride

### This is a terminal version of the famous jetpack joyride game with a star wars theme. You play the mandorian and have to protect baby yoda from a griffin which has kidnapped him. However, the griffin's cave is filled with various obstacles and has no interest in making your job easy.

## Requirements:
1. Colorama
2. Numpy

## How to Play:

- 'd' to move right
- 'w' to move up
- 'a' to move left
- 'p' to increase speed of game(powerup)
- '(space)' to activate a shield which is accessable only 3 times in the game for 10 seconds each time and with an interval of 60 sec between each usage.
- 'b' to shoot bullets over various obstacles and kill the enemy

## Obstacles:
-   Zappers : beams appear in various shapes and randomly, touching them reduces the lives and gives a 10 point penalty.
-   Magnet : Attracts the hero to it horizontally, whereever the hero is. It also has a 15 points penalty.
-   Fireballs : The final boss shoots fireballs which also has a 10 point penalty and loss of life.
## Collectables:
- Coins : collect coins which randomly appear to increase points by 5.
## Boss:
- Boss : The boss follows you in the y-axis direction and shoots fireballs and also has 9 lives, The boss is strong and can only be killed if hit by a bullet near the head.
## Powerups:
- Shield : The shield can be activated using space bar and protects the mandorian from all types of obstacles.
- Speedup : The speedup can be activated by using p and can only be used once during the game, it increases the overall speed of the game.

## Classes:
- Each of the obstacle and coins mentioned above are classes which have various methods to make it easier to use them.