# Hattrick
Hattrick Youth Academy Prediction

Open Powershell ISE, paste the script there, save it somewhere(example c:\hattrick)
Create in c:\hattrick 2 txt files, skill.txt and stars.txt

Contents of skill.txt should be something like this:

Andreescu 6.3/7 4/4 5/5 1/7 1/3

Hordiievskyi 6.3/7 3/3 7/7 3/3 3/3

Those should be your players, followed by the skills as showned in the player list. This is the order: Def PM Wing Pass Scoring
You can see there are 2 values and you have a / between them. Those are actual level and potential level. 
If you do not know actual level, write 1. If you do not know potential level, write 8
EX: player has 4 actual but dont know the potential, write 4/8. Player has potential of 7 but you dont know the level, write 1/7. Player has level 4 and potential of 6, write 6/7.

Notice on my guys, at def, i put 6.3. That is my estimation of training on them, as i know i trained them at 2 times in def+def extended, and thus forcing the script to start from that level, and not go lower.

Contents of stars.txt should be something like this:

Andreescu 5.5 5.5 4.5 5.5 4.5

Hordiievskyi 6 6 0 5.5 4

Those are the maximum stars they got on a position. The position are CD WB IM W F. If the player did not play a position, write 0.

Script needs at least 3 played positions, and at least 2-3 known level skills to work properly, otherwise there are to many variables.
I have put some conditions in the script, for example it will not estimate scoring if it didnt play as a forward. It will not estimate winger if he didn't play as a WB or W.
For best results, its better to have the player on all positions.
