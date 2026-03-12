# Solution 08: Unit Conversion & Dimensional Analysis

## 1. Problem Statement
A car is traveling at a speed of **$90 \text{ km/h}$**. Convert this speed into meters per second (**$m/s$**) using the conversion factor method.

---

## 2. Conversion Factors
To solve this, we need two standard conversion factors:
1. **Distance**: $1 \text{ km} = 1000 \text{ meters}$
2. **Time**: $1 \text{ hour} = 3600 \text{ seconds}$ ($60 \text{ min} \times 60 \text{ sec}$)

---

## 3. Step-by-Step Calculation

### Step 1: Set up the conversion chain
Multiply the initial value by fractions that equal 1, ensuring that the units we want to remove are on opposite sides (numerator vs. denominator):

$$\text{Speed} = 90 \frac{\text{km}}{\text{h}} \times \left( \frac{1000 \text{ m}}{1 \text{ km}} \right) \times \left( \frac{1 \text{ h}}{3600 \text{ s}} \right)$$

### Step 2: Cancel the units
- The **km** in the numerator cancels with **km** in the denominator.
- The **h** in the denominator cancels with **h** in the numerator.
- We are left with **m/s**.

### Step 3: Numerical calculation
$$\text{Speed} = \frac{90 \times 1000}{3600} \text{ m/s}$$
$$\text{Speed} = \frac{90,000}{3,600} \text{ m/s}$$
$$\mathbf{\text{Speed} = 25 \text{ m/s}}$$

---

## 4. Dimensional Analysis Check
- **Initial Dimension**: $[L][T]^{-1}$ (Length / Time)
- **Final Dimension**: $[L][T]^{-1}$ (Length / Time)
The dimensions match, confirming the conversion setup is logically sound.

---

## 5. Summary Tip
To convert from **km/h** to **m/s** quickly, you can always divide by **3.6**.
$$90 \div 3.6 = 25$$
