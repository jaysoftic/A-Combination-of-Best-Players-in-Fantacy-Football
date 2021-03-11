# A Combination of Best Players in Fantacy Football :india:
## Problem Statement
#### I have dataset of 147 players of fantcy football team and they wants to choose best 9 player among them for upcoming match.
For Selecting 9 best player they wants __combination__ of players with some __conditions__, which are below
<br>**1.** Player Must be __9__.
<br>**2.** The Pos (Type) of player must be following: __1 QB, 2 RB, 1 DST, 1 TE, 3 WR and 1 (RB / WR / TE)__ number of players.
<br>**3.** Patterns for Pos can be anything but which Pattern you choose they __must be following for every combination__,
for Ex pattern could be like this: (QB, RB, RB, WR, WR, WR, TE, RB/WR/TE, DST).
<br>**4.** __Total Salary__ of the combined players must be range between __49400 to 50000__.
<br>**5.** Add up __Proj.Pts__ of combined players.
<br>**6.** Maximum __limits__ of combination is __1000__.


## Solutions

- Here i solve this problem using **pandas** and **combinations of itertools** library but challanging part here was they wants **same pattern of all combinations*<br>
- Which i solved using my smart logics and with help of core python concept and it take around **85 second** to create **1000** combinaiton with satisfying all the conditions.
