# Raise A Timmy!

## Repository
<https://github.com/soupbugh/PFDA_Final_Raise_A_Timmy.git>

## Description
This program will launch an interactive game where you will take care of a virtual monster pet named "Timmy." Timmy is a very hungry monster made of muscles, it's the player's job to take care of him so he can grow to be big and strong. This is relevant to media and digital arts as I can make my art interactive in a fun way.

## Features
- **Hunger & Affection system**
	- Timmy will have a hunger and affection bar that will deplete as time goes on. If either reaches 0, Timmy gets angry and the player loses.
- **Shop & Money system**
	- Money is gained when playing with Timmy. This money will be used to buy food. Extra items might be available for purchase, such as toys or accessories. 
- **Day system**
	- Days will be counted based on a certain amount of time. For example a day can be 2 minutes, and a counter at the top will show the player how many virtual days it has been.

## Challenges
- I need to research more about Pygame and what it can offer so I can achieve the wanted features. 
- It would be nice to save the progress of a player's game, and when they return their Timmy remains unchanged from the last time they saw them. I'd have to research more on saving player progress, see if any libraries can help.
- Learn how to create animated sprites so that Timmy can move around. Maybe create unique sprites that show when a health bar is too low. 

## Outcomes
**Ideal Outcome:**
- The ideal outcome would be to have three different health bars for Timmy: Hunger, Affection, and Cleanliness.
- He would also be able to roam around his room by himself.
- Lots of shop items for food, toys, accesories and decorations for his room.
- Save progression features.
- A final item that can be bought to trigger an event, as a way to "win" the game. 
- Features from the minimal viable outcome.

**Minimal Viable Outcome:**
- The bare essential for my working outcome would include:
  - At least idle movement from Timmy.
  - A health and affection bar. 
  - A starting amount of food.
  - A lose condition (not enough food or affection)

## Milestones

- **Week 1**
  1. Create place holder assets and create the display window.
  2. Make Timmy move around (either randomly or by using the arrow keys)
  3. Create hunger bar & make list of foods that when given to Timmy (via a click or drag), it increases his hunger bar.

- **Week 2**
  1. Use the similar hunger system to create an affection system. This time when Timmy is clicked on, the player will be given money and his affection will go up.
  2. Create a simple shop, where the money gained can be used to buy more food. 
  3. Create the lose condition if hunger or affection reaches 0.

- **Week 3**
  1. Add a clock that tracks the player's days.
  2. Implement more items to the shop.
  3. If I have time, adding a Cleanliness bar. When this is added I could also make it where if one action is taken, the health of another action bar goes down.

- **Week 4 (Final)**
  1. Polish up assets if I haven't already.
  2. Create a button that restarts the game once player loses. 
  3. Finalize and polish anything that could be breaking the game. 