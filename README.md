# haikuConflictWarmUp
Overview: Resolve merge conflicts on different branches to create one branch with a complete and correct Haiku.

Directions:
There are 4 Branches in this repo , master, 'a', 'b', and 'c'. Within branches a, b, and c, there is a file called haiku.txt. Each branch has 1 line of a 3 lined haiku within its own haiku.txt file.

Your goal is to bring the entire haiku into the 'a' branch.

Start by merging the 'c' branch into the 'b' branch. You should get a merge conflict, go into your editor and keep both of the lines and remove the conflict syntax. Don't leave whitespace at the top , use up lines 1 and 2.

Next merge the 'b' branch into the 'a' branch, you should get another merge conflict. Keep all 3 lines and remove the conflict syntax.

Within your haiku.txt file , you should see this completed haiku:

```
Over-ripe sushi,
The Master
Is full of regret.
```
