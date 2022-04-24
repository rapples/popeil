# popeil
Single Page HTML5/CSS/Javascript example of a "the price is right" style game using Youtube video links to old Ron Popeil vides.

The code is a combination of routines garnered via stack overflow and other documentation.  Presents a best effort
single page game. Plays with a tap on Chrome desktop. Plays correctly on Safari desktop. Plays with a tap on Safari mobile.

goals: Consistant play without tap on a variety of device types.

Logic -> 

there is the initial array of starting-time url, midpoint-time url, and ending-time urls
another array of random numbers is made with pairs of the random number and that same random number plus one.
the final array is built that allows the videos to play in a random sequence pair.

Button properties are modified as the code cycles through allowing better instruction to the play of what's going on.

