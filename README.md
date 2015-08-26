# Avalanche
Control a skier in his attempt to escape endless waves of snowballs!

[Play Avalanche][live-link]
[live-link]: http://shoecar.github.io/avalanche

<b>Features</b>
- Three speed settings for varied difficulty
- High score tracked by a cookie for each speed setting
- Parallax background responds to user's movements

<b>How It Works</b>
- Internal game engine written in vanilla javascript
- HTML 20x20 grid cells with changing classes to update object positions
- jQuery changes player class based on user input
- New wave of snowballs initialized every 10th time iteration
- Snowballs in wave given random speed for wave variation
- Snowballs classes are updated based on their internal settings
