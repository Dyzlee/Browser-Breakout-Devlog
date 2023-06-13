# Browser-Breakout-Devlog
Infos and updates for the game Browser Breakout

## Description
Browser Breakout is a small game that comes in the form of a Chrome Extension. It makes use of the DOM-Elements of a website and transforms visible elements into bricks. These bricks can then be destroyed by the player using the ball and paddle - just like in the original Breakout game!

![Demo of Browser Breakout on Wikipedia](assets/bb-demo.gif)

## Download
[Chrome Download Link](https://chrome.google.com/webstore/detail/browser-breakout/oefbdmhkfnipjlgkemmcfhdijpdmjcmp)

## Release notes
### 0.71.0
- Paddle width & height and ball radius now depend on the players window size
- Some bug fixes
- The game will now react if the user changes the window size while the game is active
- Tweaked some internal settings to balance the game

### 0.70.0
- Some bug fixes
- Upgraded the brick generation algorithm to find more potential bricks on the screen

### 0.69.0
- Bricks won't overlap anymore and the selection of what DOM-Element becomes a brick will always be the same (given the same website and POV)
- Removed the "Bricks Amount" setting since the amount of generated bricks will now depend on the website and POV
- The content of bricks now disappear on contact

### 0.68.0
- Initial release