Assumption:

Assume that √2 is rational. Then there exists a pair of positive integers a and b in lowest terms such that,

√2 = a/b ⇒ a = √2b

squaring both sides: a² = 2b²

Now, instead of thinking about this completely algebraically or in 2 dimensions, we introduce a third dimension, height y, to visualize 
this equation as the volumes of cuboids.

We let the length and the breadth of the cuboids be equal.

So the equation becomes:

y×a² = 2×y×b² 

That is, one larger cuboid with base a×a has the same volume as two smaller cuboids (each b×b×y)

Geometric Construction:

![Larger cuboid](https://github.com/BongoLogic/3D-Proof-of-Irrationality/blob/main/photo_2025-06-12_23-07-52.jpg?raw=true)

Imagine placing the two smaller cuboids inside the larger one diagonally, from opposite corners. Visually, they will overlap in the center, leaving uncovered regions at the two opposite sides.

![smaller cuboid1]

![smaller cuboid2]

![union of smaller cuboids]

![smaller cuboids in the larger one]

From the top view:

• You see the larger cuboid as a square base of a×a.

• The two smaller cuboids are inserted from opposite corners.

• They overlap in the center and leave two corner regions uncovered.

According to the Carpets Theorem, the region og overlap will be equal to the uncovered region, so adding a y component preserves the equality. (Refer to the README file for more details on the Carpets theorem)

Let's analyze the volume of these parts:

• Overlapping central cuboid:

Dimensions are (2b-a) × (2b-a) × y, so its volume is: y(2b-a)²

•Each uncovered corner cuboid:

Dimensions are (a-b) × (a-b) × y, so each has volume: y(a-b)²
There are two such uncovered regions.

(I am calling the Carpets Theorem with a height component, "Volume Identity)

Volume Identity:

From the construction, we see that:

Volume of the centre overlap = Total volume of the two side gaps, that is:
y(2b-a)² = 2y(a-b)²

This equation is in the same form as our original equation from the start, that is, a²y = 2b²y, but the new equation is now with smaller integers:

• New a' = y(2b-a)

• New b' = y(a-b)

This creates a smaller solution to the equation, and you can repeat this process indefinitely.

Contradiction (Infinite Descent):

If √2 = a/b, then we have now produced a smaller pair of (a' and b') of positive integers also satisfying the same equation. Repeating this process gives infinitely many smaller and smaller positive integer pairs.

But this is impossible, you can't have an infinite descending sequence of positive integers.

Hence, our original assumption that √2 is rational must be false.

Therefore, √2 is irrational.
