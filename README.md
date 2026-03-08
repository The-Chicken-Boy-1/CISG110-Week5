# CISG110-Week5
## Devlog

When I see the line of code _sprite.modulate = Color(r, g, b), my best guess is that the period is used to access something that belongs to the _sprite object. In this case, it looks like it is accessing the modulate property of the sprite. So the code is basically telling the program to change the color settings of that sprite. The Color(r, g, b) part probably means red, green, and blue values that mix together to create a certain color. So overall, the line of code is setting the sprite’s color tint using those RGB values.

From the documentation, I learned that the modulate property changes the color tint of a node that inherits from CanvasItem, like sprites. Instead of changing the original image file, it overlays a color on top of the sprite. This can make the sprite look darker, lighter, or completely different depending on the RGB values used. For example, lowering some of the color values can make the sprite look dim or tinted, while higher values can make it brighter or change the color completely.

When I messed with the modulate setting in the Visibility section of the Inspector, I noticed that the Player sprite’s color changed in the 2D window. If I moved the color toward red, the character started looking red, and if I changed the brightness it could look darker or faded. This helped me guess that the code is basically doing the same thing but through programming instead of manually in the Inspector. So _sprite.modulate = Color(r, g, b) is probably telling the game to dynamically change the color of the player sprite during gameplay.

## Open-Source Assets
- [Cat sprites](https://toffeecraft.itch.io/cat-pixel-mega-pack)
- [Kenny's abstract platformer set](https://kenney.nl/assets/abstract-platformer)
- [Rainy Hearts font](https://www.dafont.com/rainyhearts.font)
