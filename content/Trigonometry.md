---
dg-publish: true
---

Trigonometry can feel like a maze of Greek letters and ratios, but at its heart, it is just a tool for decoding the relationships between the angles and sides of a triangle. Whether you are prepping for advanced math competitions or just strengthening your geometry toolkit, mastering these concepts will definitely help you break down complex geometric problems with ease.

Let's dive into the core fundamentals of right-triangle trigonometry and see how we can expand those rules to conquer any triangle using the Law of Cosines.

## The Foundation: SOH-CAH-TOA

When you are dealing with **right triangles** (triangles where one angle is exactly 90°), the easiest way to remember your basic trigonometric functions is the famous mnemonic **SOH-CAH-TOA**.

These ratios are entirely based on the position of a given acute angle ($\theta$) relative to the sides of the right triangle:

- **SOH (Sine):** $\text{Sine} = \frac{\text{Opposite}}{\text{Hypotenuse}}$
    
- **CAH (Cosine):** $\text{Cosine} = \frac{\text{Adjacent}}{\text{Hypotenuse}}$
    
- **TOA (Tangent):** $\text{Tangent} = \frac{\text{Opposite}}{\text{Adjacent}}$
    

> ⚠️ **Important Reminder:** SOH-CAH-TOA ratios apply **ONLY** to right triangles! If your triangle doesn't have a 90° angle, plugging numbers directly into these basic ratios will throw off your calculations completely.

## Common Trigonometric Values to Memorize

In many geometry problems, certain angles show up repeatedly. Memorizing the values for 0°, 30°, 45°, 60°, and 90° will save you invaluable time.

Here is a quick reference table of the standard values:

| **Angle (θ)** | **Sine (sin)**       | **Cosine (cos)**     | **Tangent (tan)**    |
| ------------- | -------------------- | -------------------- | -------------------- |
| **0°**        | $0$                  | $1$                  | $0$                  |
| **30°**       | $\frac{1}{2}$        | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{3}}{3}$ |
| **45°**       | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$                  |
| **60°**       | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$        | $\sqrt{3}$           |
| **90°**       | $1$                  | $0$                  | _Undefined_          |

## Breaking Free of Right Triangles: The Law of Cosines

What happens when you aren't working with a right triangle? That is where the **Law of Cosines** comes in. Think of the Law of Cosines as the ultimate, upgraded version of the Pythagorean theorem that works for **any triangle**, regardless of its angles.

For any triangle with side lengths $a$, $b$, and $c$, and angles $A$, $B$, and $C$ (where angle $A$ is opposite side $a$, and so on), the Law of Cosines states:

$$a^2 = b^2 + c^2 - 2bc \cos(A)$$

Depending on which side you are trying to solve for, you can write the formula in any order—just make sure that the isolated side matches the angle inside the cosine function:

- $b^2 = a^2 + c^2 - 2ac \cos(B)$
    
- $c^2 = a^2 + b^2 - 2ab \cos(C)$
    

### The Secret Pythagorean Connection

Have you ever noticed how similar the Law of Cosines looks to the Pythagorean theorem ($c^2 = a^2 + b^2$)? That isn't a coincidence!

If you use the Law of Cosines on a right triangle where angle $C = 90^\circ$, you plug in $\cos(90^\circ)$. As we saw in our table above, $\cos(90^\circ) = 0$. Because that entire trailing term ($2ab \cdot 0$) becomes zero, the formula collapses beautifully back into the familiar Pythagorean theorem:

$$c^2 = a^2 + b^2$$

### Putting It to the Test

Let's look at a practical example. Suppose you have a triangle with side $b = 6$, side $c = 10$, and an included angle $A = 120^\circ$. You need to find side $a$.

1. **Set up the formula:**
    
    $$a^2 = 6^2 + 10^2 - 2(6)(10) \cos(120^\circ)$$
    
2. **Simplify the squares and multiplication:**
    
    $$a^2 = 36 + 100 - 120 \cos(120^\circ)$$
    
    $$a^2 = 136 - 120 \cos(120^\circ)$$
    
3. **Evaluate the cosine:** Using trigonometric identities, we find that $\cos(120^\circ) = -\frac{1}{2}$.
    
    $$a^2 = 136 - 120\left(-\frac{1}{2}\right)$$
    
    $$a^2 = 136 + 60 = 196$$
    
4. **Solve for $a$:**
    
    $$a = \sqrt{196} = 14$$
    

With a final side length of 14, you have successfully solved a non-right triangle problem using pure trigonometric strategy. Keep these core patterns, formulas, and common angles close at hand, and you will be ready to dismantle any triangle problem that comes your way!