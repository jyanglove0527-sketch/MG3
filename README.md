# MG3
## Devlog
## Devlog
1. The default value for floats and ints is 0, the default value for bools is false, and the default value for strings is empty (no text).

2. My code does not call the Update method in this assignment. Unity calls the Update method automatically every frame, which is dozens of times every second.

3. The TimerText class uses the timer to keep track of how long the game lasts. When the game starts, the Start() method calls BeginTimer to set the timer to 30 seconds. Then, every frame, the Update() method checks if the timer is finished using IsFinished(), and when the time runs out, it calls the GameOver method.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)