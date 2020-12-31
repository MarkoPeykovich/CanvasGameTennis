# CanvasGameTennis
Javascript, HTML Tennis game

This is a simple HTML/Javascript Canvas tennis game. It represents an upgraded version of the game (code) that I found on the youtube 
(under the title "Code Ping Pong Game Using JavaScript and HTML5"). But, in my version of the game, the paddles/rackets of the user-player 
are not moved by mouse movements, they are moved by keyboard buttons (keys) and these paddles/rackets do not move only vertically along 
the fixed y-axis, they move horizontally along the dynamic x-axis also (according to the preferences of the user-player). Next, in my version, 
the racket/paddle of the computer-player moves along the x-axis randomly back and forth, while along the y-axis it moves according to the 
original code. Both paddles/rackets are bounded to move inside the boundaries of each half of the canvas rectangle. Besides, the speed of 
the ball in my version of the code is not constantly increasing, it is rather determined randomly via Math.random() inside the update() of 
each frame of the game() and in the range from very slow to very fast, with the objective of creating an authentic feeling of playing real 
tennis, as much as possible. Below the canvas, a counter of the game rounds is shown (Runda broj:).
