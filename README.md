# minigame 2
## Devlog
1. In step 5 (located in the ColorChange script), I encountered an error stating that "else could not start a statement". This occurred because I had all of my else if statements nested in the brackets of the if statement. This error led to various other syntax errors such as "'()' expected", "';' expected", and "invalid expression term: else". I solved this by simply cutting all of my else if statements, and pasting them outside of the if statement brackets. 

2. I think this line of code: "_spriteRenderer.color = new Color(r, 0.2f, 0.2f);" is directly creating a specific color with an inputted "r" value and set values for "g" and "b". I believe the period is used to indicate that this color will be specific to spriteRenderer, meaning that this sprite will change to the color created. I surmise that the term "new" is used to indicate that the color being created will replace the previous color of "spriteRenderer".

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
