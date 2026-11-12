# WeeklyChallenge 10
Morgan Lincicum

Use the arrow keys to move the player character. Press E next to the donkey to interact with it.

## Reflection Questions
### What object did you make interactive using raycasting?
I made the donkey interactable.
### How does raycasting differ from collision detection?
Raycasting allows the use of the mouse as well as more precision compared to collision detection. While collision detection 
requires you to use bounding boxes and loop through arrays, raycasting is more focused on one line.
### Why must a ray have both an origin and a direction?
It needs to know where the line starts and where it is pointing at, just like a ray in math. Knowing the direction means nothing
if you don't know where it needs to go, and vice versa.
### What sound effect did you choose and why?
I chose a donkey braying because it is a recognizable sound to show that you've interacted with the donkey.
### How did adding sound and interaction improve your scene?
It makes it feel much more immersive. Although it's not complicated, it adds a further element of interaction and 
direct feedback to the player.
### What additional interactive object would you add if you had another hour?
Originally I was going to make you be able to hit the donkey (poor guy) and play different animations for the player
and the donkey when you do, but I ran into a ton of problems with the raycasting and the donkey for some reason (raycasting
with every other object in the scene worked, and this exact donkey model worked for Diti, and the AI chatbot in the codespace
thought it all looked fine, so I'm genuinely baffled) so I ran out of time. With more time, I might also make the door and
or the fountain interactable. 