---
dg-publish: true
---

2020 AMC 10A Problem 12      
Triangle Picture HERE: https://imgur.com/a/mOAakqA
Triangle AMC is isosceles with AM = AC. Medians MV and CU are perpendicular to each other, and MV = CU = 12. What is the area of AMC?
What I knew: I knew from looking at triangle AMC is that something I could do to help me was to draw a line between points U and V. It might not look like much, but once I drew that line, I noticed that triangle AUV is congruent to triangle AMC, and that it is 1/4 of triangle AMC. 
What I didn't know: How to calculate the area of UVMC
How was I supposed to calculate it? There is a formula to find the area of a quadrilateral with diagonals that are perpendicular: Diagonal1 ** Diagonal2 ** 1/2, which if I plugged in the numbers, it would result in 12 ** 12 ** 1/2, which is 72. 72 is 3/4 of the whole triangle, so we need to find the area of AUV, and all we have to do is divide 72 by 3, which is 24, then add 24 to 72, which gets us 96, which is our answer.
How does the formula work?   Imagine drawing a tight rectangle around your shape, where the sides of the rectangle touch the four outer points of your diagonals.

Once you do that, you notice that the **width** of the rectangle is the exact same length as Diagonal 1, and the **height** of the rectangle is the exact same length as Diagonal 2.

To find the area of this entire rectangle, all you have to do is multiply the width by the height, which is just Diagonal 1 \(\times \) Diagonal 2.

But we don't want the area of the whole rectangle—we only want the shape inside it. Because the diagonals cross at a perfect \(90^{\circ }\) angle, they create pairs of identical triangles. Every triangle inside your shape has a twin triangle filling up the empty space outside your shape.

Since the space inside your shape and the empty space outside it are exactly equal, your shape takes up exactly half of the rectangle.

So, all we have to do is take the rectangle's total area (Diagonal 1 \(\times \) Diagonal 2) and divide it by 2. That gets us \(\text{Diagonal } 1 \times \text{Diagonal } 2 \times \frac{1}{2}\), which is our answer.
