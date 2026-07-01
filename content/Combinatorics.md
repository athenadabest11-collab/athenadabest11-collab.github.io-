---
dg-publish: true
---
Combinatorics is one of the most intimidating parts of competition math.

Not because the math is advanced.

Usually, it is because the problem looks impossible.

A typical AMC counting problem gives you something like:

- 10 people,
    
- 8 books,
    
- several restrictions,
    
- different arrangements,
    
- multiple cases.
    

Your first thought:

_"There are way too many possibilities. How am I supposed to count all of them?"_

That reaction is exactly what the problem is designed to create.

The biggest secret in combinatorics:

**Strong competitors do not count more. They organize better.**

The goal is not to list every possibility.

The goal is to find the structure that makes most possibilities disappear.

---

# The Beginner Mistake: Counting Before Understanding

A common beginner approach:

"Let me just try some cases."

Then 5 minutes later:

"I lost track."

This happens because humans are terrible at remembering unorganized possibilities.

A competition mathematician asks:

"What is the thing that actually controls the count?"

That might be:

- the first choice,
    
- the last position,
    
- a restriction,
    
- symmetry,
    
- a pattern.
    

Find the controlling idea, and the counting becomes mechanical.

---

# Strategy 1: The Fundamental Counting Principle

The foundation of almost all counting:

If one action has (a) choices and another has (b) choices:

[  
a \times b  
]

total possibilities.

Example:

A password has:

- 3 possible letters,
    
- followed by 4 possible numbers.
    

Total:

[  
3 \times 4=12  
]

possibilities.

Simple.

But AMC takes this idea and hides it.

The challenge is recognizing what the "steps" actually are.

---

# Strategy 2: Count the Opposite (The Most Powerful Beginner Upgrade)

Sometimes the thing you want is annoying to count.

So count everything else.

Example:

"How many numbers from 1 to 100 have at least one 7?"

Counting directly:

7, 17, 27, 37...

Messy.

Instead:

Count numbers with **no 7**.

Then subtract.

This is called the complement method.

The logic:

[  
\text{wanted} = \text{total} - \text{unwanted}  
]

Many hard-looking AMC problems collapse using this.

---

# Strategy 3: The "Slots" Method

Whenever you see:

- arrangements,
    
- seating,
    
- ordering,
    
- passwords,
    

draw slots.

Example:

How many ways can 5 people stand in a line?

Imagine:

[  
_ \ _ \ _ \ _ \ _  
]

First spot:

5 choices.

Second spot:

4 choices.

Third:

3 choices.

Then:

[  
5 \times 4 \times 3 \times 2 \times 1  
]

The answer is:

[  
5!  
]

The important part is not memorizing factorials.

It is seeing the slots.

---

# Strategy 4: The "Do Not Double Count" Rule

This is where competition counting becomes serious.

Many wrong answers happen because the same object gets counted twice.

Example:

A student counts:

- choosing A then B,
    
- choosing B then A.
    

But if order does not matter, those are actually the same group.

The question:

"Does the order matter?"

is one of the most important questions in combinatorics.

If order matters:

Arrangement.

If order does not matter:

Selection.

---

# Strategy 5: Use Symmetry

This is an advanced competition habit.

Sometimes many cases are identical.

Example:

A circle has 6 equally spaced points.

How many ways can you choose 2 points?

A beginner might draw every possibility.

A competitor notices:

Every point behaves the same.

There are:

[  
6  
]

choices for the first point.

Then:

[  
5  
]

choices for the second.

But each pair was counted twice.

So:

[  
\frac{6 \times 5}{2}  
]

The symmetry removes the mess.

---

# Strategy 6: Recursion — The Hidden Pattern Behind Many Problems

Some counting problems grow step-by-step.

Instead of solving the whole thing at once:

Look at the previous case.

Example:

How many ways can you climb stairs if you can move 1 or 2 steps?

For (n) stairs:

The final move was either:

- one step,
    
- two steps.
    

So:

[  
f(n)=f(n-1)+f(n-2)  
]

The problem becomes a pattern.

This idea appears everywhere in advanced counting.

---

# A Real AMC-Style Example

A club has 6 members. How many ways can they choose a president and vice president?

A beginner:

"Choosing two people."

Maybe:

[  
\binom{6}{2}  
]

But wait.

The positions are different.

Being president is not the same as being vice president.

Order matters.

President:

[  
6  
]

choices.

Vice president:

[  
5  
]

choices.

Total:

[  
6 \times 5=30  
]

The trick was recognizing the structure.

---

# The Advanced Combinatorics Mindset

The biggest shift:

Beginners ask:

> "How can I list all the possibilities?"

Competitors ask:

> "What information determines all possibilities?"

A counting problem is rarely about counting.

It is about finding the right viewpoint.

The strongest solvers use:

- symmetry,
    
- complements,
    
- recursion,
    
- case organization,
    
- invariants.
    

They turn a chaotic problem into a machine.

---

# Final Truth

Combinatorics feels impossible when every possibility looks different.

The moment you find the pattern, everything becomes identical.

That is the beauty of counting.

You are not trying to see every possibility.

You are trying to see why thousands of possibilities are secretly the same.

That is the art of counting. 🔥