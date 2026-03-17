# Infinite Series – Ant Movement

## Problem
An ant starts at the origin and moves:

1 m east, 1/2 m north, 1/3 m west, 1/4 m south, 1/5 m east, ...

Find the final position.

---

## Step 1: Separate directions

### X-direction (East/West):

x = 1 - 1/3 + 1/5 - 1/7 + ...

This is an alternating series:

x = π / 4

---

### Y-direction (North/South):

y = 1/2 - 1/4 + 1/6 - 1/8 + ...

Factor out 1/2:

y = (1/2)(1 - 1/2 + 1/3 - 1/4 + ...)

This series equals:

y = (1/2) ln(2)

---

## Step 2: Final position

(x, y) = (π/4, (1/2)ln(2))

---

## Final Answer

x = π / 4 ≈ 0.785  
y = (1/2) ln(2) ≈ 0.346
