# InfiniteMatrix
 An introductory game to CS 498 Game Dev
 
 1. Complete the Tutorial:

Complete this tutorial on making a simple game by Ray Wenderlich. Do not skip the tutorial and just grab the finished code; complete the tutorial. It teaches almost all of what you need to know to implement the additional features below (features that are not included in the finished tutorial code posted at the site).

2. Add a health system for the player. Your health system should:

Be displayed as a bar or number on the UI
Decrease their health value upon collision with an obstacle
Stop the player only when their health value this 0
Have a max health value
Correctly reset to its max health value when the game is restarted

3. Add a score. Your score should:

Be displayed as a number on the UI
Increment only when the player successfully goes through a hole in an obstacle
Reset to 0 when the game is restarted

4. Add health packs. Your health packs should:

Be a collidable object
Be destroyed upon collision with the player
Be destroyed shortly after if the player goes past them
Increase the health value upon collision with the player, up to a max health value
Appear in tunnels at a randomized rate, but never more than once per tunnel
Have a semi randomized location in the tunnel that does not collide with other objects

5. Add player projectile attacks. Attacks should:

Create a projectile on left mouse click that shoots forward down the tunnel faster than the player
The projectile is destroyed upon collision with anything and after a short duration
Have a short cooldown on shooting projectiles
The projectile is created at the player/mouse position

6. Add enemies. Enemies should:

Be a collidable object
Be destroyed on collision with projectiles or the player
Increase the score on destruction by a projectile
Decrease the health value on collision with the player
Be destroyed shortly after if the player goes past them
The visual representation of the enemy is up to you…it can be simple.

7. Increase the player speed over time. The player speed increase should:

Get faster over time, either directly based on time, or based on the player score
Increase at a rate that is noticeable but does not ramp up the difficulty too fast

8. Add one creative modification that is unique to your game. Some ideas:

Health bar decreases along a gradient of colors
Add screen shake on collision with barriers and enemies
Color of the walls change depending on player health
