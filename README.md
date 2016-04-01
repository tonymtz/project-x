# ProjectX


![Current state](https://raw.githubusercontent.com/tonymtz/project-x/b3c72c251be1f54c0987f3c30910ae3c765ea8ac/Promo%20images/Promo_Gif_6.gif)

Trello Board:
https://trello.com/b/IHmhQEse/project-x

## Tools
Using Unity *5.3.3*

## Project Structure

I suggest to use this structure, so we can work better without mixing different assets:

- Animations
- Prefabs
- Scenes
- Scripts
- Sprites


## Best Practices

- Since scenes are saved as binaries, I think we can work better having all entities in prefabs and updating them instead of making modifications to the entities directly in the scene. In this fashion we can work at the same time in different scenes to avoid conflicts and reusing the same prefabs.
