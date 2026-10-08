# Jason Jung - minigame 2
## Devlog
1. I didn't get any errors in my code so the error I fixed in the if-statement was that after the if, there wasn't an expression as _timeleft <= 0.0 didn't have parentheses to make it an expression.
2. I think that line of code changes the color from bright red to dark red. The two 0.2fs are probably the color value for the color red and the r corresponds to the brightness value of the color. When the chest is hit with the spell, r goes down which makes the red color darker.
3. I think the period is to show that _spriteRenderer is parenting color. This means that they are connected and color can influence _spriteRenderer and the other way around. I think new means that a new color is being created based on the new values when the values change.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
