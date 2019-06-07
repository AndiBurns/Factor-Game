# Factor-Game
A strategy game for two players (comp vs. human) about factoring numbers<p/>

Developed by Andi Keeley<br/>
started on the evening of 6/5/2019<br/>
based on number theory studied at Bridgewater State University<p/>

The game starts with a Magic Number. The player can set a Magic Number, or have the game<br/>
choose one at random. The game will factor that number automatically,<br/>
but the results can be hidden to allow the player to practice factoring, and then shown<br/>
to confirm. Gameplay proceeds in turns. First, the comp will select one of the factors<br/>
(possibly the number itself), and then all multiples of that factor (including the factor itself)<br/>
are eliminated. Next, the player selects a factor that has not yet been eliminated, and all<br/>
multiples of that factor are eliminated. Play proceeds back and forth like this until a player<br/>
is forced to choose 1 (the losing move).<p/>

The algorithms used here are not necessarily optimized. This should not be understood as a high<br/>
performance application. Checking for primeness/prime factorization and determining winning<br/>
strategy are all done by brute force methods.<p/>

Tested on Chrome Version 75.0.3770.80 (Official Build) (64-bit) and Firefox 67.0.1 (64-bit),<br/>
both running on Microsoft Windows 10 Home Version 10.0.17134 Build 17134.<br/>
Not yet tested for tablets or mobile devices.<p/>
