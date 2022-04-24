# popeil
Single Page HTML5/CSS/Javascript example of a "the price is right" style game using Youtube video links to old Ron Popeil vides.

The code is a combination of routines garnered via stack overflow and other documentation.  Presents a best effort
single page game. Plays with a tap on Chrome desktop. Plays automaticly on Safari desktop. Plays with a tap on Safari mobile.

goals: Consistant play without tap on a variety of device types.  End of Game.  Scoring for mult-player.

Logic -> 

There is the initial array of starting-time url, midpoint-time url, and ending-time urls.
An array of random numbers is made with pairs of the random number and that same random number plus one.
The final array is built pushing the url data.  This allows the videos to play in random sequence pairs.

Button properties are modified as the code cycles through allowing better instruction to the play of what's going on.

