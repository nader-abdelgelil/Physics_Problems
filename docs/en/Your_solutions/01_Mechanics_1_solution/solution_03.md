# Path Intersection – Relative Motion

## Problem
Alice: A(t) = (2 + t, 8 - 3t)  
Bob:   B(t) = (2t - 1, 2t + 2)

Check:
1. Do they collide (same time & position)?
2. If not, find minimum distance and when it occurs.

---

## Step 1: Check collision condition

For collision:

A(t) = B(t)

So:

2 + t = 2t - 1   ...(1)  
8 - 3t = 2t + 2  ...(2)

---

## Step 2: Solve equations

From (1):

2 + t = 2t - 1  
t = 3

From (2):

8 - 3t = 2t + 2  
6 = 5t  
t = 6/5

---

## Step 3: Conclusion

t values are different → no collision

---

## Step 4: Distance function

Distance squared:

D²(t) = [(2+t) - (2t-1)]² + [(8-3t) - (2t+2)]²

Simplify:

x-part: 3 - t  
y-part: 6 - 5t

So:

D²(t) = (3 - t)² + (6 - 5t)²

---

## Step 5: Expand

D²(t) = (9 - 6t + t²) + (36 - 60t + 25t²)

D²(t) = 45 - 66t + 26t²

---

## Step 6: Minimize

Take derivative:

d(D²)/dt = 52t - 66

Set = 0:

52t = 66  
t = 33/26

---

## Step 7: Minimum distance

Substitute:

x = 3 - t = 3 - 33/26 = 45/26  
y = 6 - 5t = 6 - 165/26 = -9/26

D² = (45/26)² + (-9/26)² = 81/26

D = √(81/26) = 9 / √26

---

## Final Answer

- No collision  
- Minimum distance occurs at: t = 33/26  
- Minimum distance: D = 9 / √26 ≈ 1.76
