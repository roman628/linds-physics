# PHYS 140 Final Exam - Practice Test

**Format:** 7 questions, 2 hours | **Goal:** Practice writing for partial credit

---

## Question 1: Projectile Motion [25 pts]

A soccer ball is kicked from ground level at 30° with initial speed 25 m/s.

**(a)** Find x and y components of initial velocity. **[5 pts]**
**(b)** Find maximum height. **[8 pts]**
**(c)** Find time in air. **[7 pts]**
**(d)** Find horizontal range. **[5 pts]**

### Solution:

**(a) [5 pts]**
```
Given: v₀ = 25 m/s, θ = 30°
v₀ₓ = v₀cos(θ) = 25cos(30°) = 21.7 m/s
v₀ᵧ = v₀sin(θ) = 25sin(30°) = 12.5 m/s
```
**Partial credit:** Diagram + formulas = 2 pts

**(b) [8 pts]**
```
At peak: vᵧ = 0
vᵧ² = v₀ᵧ² - 2g(y - y₀)
0 = (12.5)² - 2(9.8)y
y = 156.25/19.6 = 7.97 m
```
**Key:** State vᵧ=0 (1pt) | Equation (3pts) | Solve (3pts) | Units (1pt)

**(c) [7 pts]**
```
y = y₀ + v₀ᵧt - ½gt²
0 = 0 + 12.5t - 4.9t²
t(12.5 - 4.9t) = 0
t = 12.5/4.9 = 2.55 s
```
**Key:** Setup y=0 (3pts) | Algebra (2pts) | Answer (2pts)

**(d) [5 pts]**
```
x = v₀ₓt = 21.7(2.55) = 55.3 m
```
**Key:** Formula (2pts) | Calculation (2pts) | Units (1pt)

---

## Question 2: Forces on Incline [25 pts]

A 2.7 kg box on 34° incline with μₖ = 0.15.

**(a)** Draw free body diagram. **[6 pts]**
**(b)** Find acceleration if sliding down. **[10 pts]**
**(c)** Find minimum μₛ to prevent sliding. **[9 pts]**

### Solution:

**(a) [6 pts]**
```
Draw:
- Box on incline
- Weight mg (straight down)
- Normal N (perpendicular to surface)
- Friction f (up the incline)

Components:
- mg sin(34°) parallel to incline
- mg cos(34°) perpendicular to incline
```
**Key:** All forces labeled (4pts) | Components shown (2pts)

**(b) [10 pts]**
```
Perpendicular: N = mg cos(34°)
                N = 2.7(9.8)(0.829) = 21.9 N

Parallel: mg sin(34°) - fₖ = ma
          mg sin(34°) - μₖN = ma
          2.7(9.8)(0.559) - 0.15(21.9) = 2.7a
          14.8 - 3.29 = 2.7a
          a = 4.26 m/s²
```
**Key:** N equation (2pts) | Parallel equation (3pts) | Substitute fₖ (2pts) | Solve (3pts)

**(c) [9 pts]**
```
For no sliding: a = 0
mg sin(θ) = fₛ,max = μₛN = μₛmg cos(θ)
μₛ = sin(θ)/cos(θ) = tan(34°) = 0.67
```
**Key:** State a=0 (2pts) | Setup (4pts) | Simplify (3pts)

---

## Question 3: Energy Conservation [25 pts]

A 100 kg roller coaster starts at rest at h₁=45m, drops to h₂=0m, climbs to h₃=25m and stops. Friction acts from h₂ to h₃ over 25m distance.

**(a)** Find PE at h₁. **[5 pts]**
**(b)** Find speed at h₂. **[8 pts]**
**(c)** Find energy lost to friction. **[12 pts]**

### Solution:

**(a) [5 pts]**
```
PE = mgh₁ = 100(9.8)(45) = 44,100 J
```
**Key:** Formula (2pts) | Calculate (2pts) | Units (1pt)

**(b) [8 pts]**
```
Conservation (A→B frictionless):
mgh₁ + 0 = 0 + ½mv²
gh₁ = ½v²
v = √(2gh₁) = √(2×9.8×45) = 29.7 m/s
```
**Key:** Conservation equation (3pts) | Cancel m (1pt) | Solve (3pts) | Units (1pt)

**(c) [12 pts]**
```
Energy at B: KE = ½(100)(29.7)² = 44,100 J
Energy at C: PE = 100(9.8)(25) = 24,500 J
Energy lost = 44,100 - 24,500 = 19,600 J
```
**Key:** Calculate both energies (4pts each) | Subtract (4pts)

---

## Question 4: Circular Motion [25 pts]

A 1000 kg car rounds flat curve, radius 50m, speed 15 m/s.

**(a)** Find required centripetal force. **[8 pts]**
**(b)** If μₛ=0.60, will car make turn? **[10 pts]**
**(c)** Find maximum safe speed. **[7 pts]**

### Solution:

**(a) [8 pts]**
```
Fc = mv²/R = 1000(15)²/50 = 4500 N
```
**Key:** Formula (3pts) | Calculate (4pts) | Units (1pt)

**(b) [10 pts]**
```
Friction provides Fc:
fmax = μₛN = μₛmg = 0.60(1000)(9.8) = 5880 N

Since fmax (5880N) > Fc (4500N):
YES, car will make the turn
```
**Key:** State friction=Fc (2pts) | Calculate fmax (3pts) | Compare (3pts) | Conclude (2pts)

**(c) [7 pts]**
```
At max: μₛmg = mv²/R
v = √(μₛgR) = √(0.60×9.8×50) = 17.1 m/s
```
**Key:** Setup equation (4pts) | Solve (2pts) | Units (1pt)

---

## Question 5: Momentum & Collision [25 pts]

A 0.15 kg hockey puck at 35 m/s is caught by 70 kg goalie at rest.

**(a)** Find goalie's recoil velocity. **[12 pts]**
**(b)** Find kinetic energy lost. **[13 pts]**

### Solution:

**(a) [12 pts]**
```
Momentum conservation (inelastic):
mpvp + 0 = (mp + mg)v'
0.15(35) = (0.15 + 70)v'
5.25 = 70.15v'
v' = 0.075 m/s
```
**Key:** Diagram (2pts) | State conservation (2pts) | Write equation (4pts) | Solve (3pts) | State "inelastic" (1pt)

**(b) [13 pts]**
```
KEᵢ = ½(0.15)(35)² = 91.88 J
KEf = ½(70.15)(0.075)² = 0.20 J
ΔKE = 91.88 - 0.20 = 91.68 J lost
```
**Key:** Initial KE (5pts) | Final KE (5pts) | Subtract (3pts)

---

## Question 6: Work & Friction [25 pts]

A 1200 kg car's engine shuts off at 15 m/s. It slows to 10 m/s over distance d. Friction μₖ=0.3.

**(a)** Find deceleration. **[8 pts]**
**(b)** Find distance d. **[10 pts]**
**(c)** Find work done by friction. **[7 pts]**

### Solution:

**(a) [8 pts]**
```
f = μₖmg
F = ma → μₖmg = ma
a = μₖg = 0.3(9.8) = 2.94 m/s²
Direction: a = -2.94 m/s² (opposes motion)
```
**Key:** Write f=μₖmg (2pts) | a=μₖg (3pts) | Calculate (2pts) | Sign (1pt)

**(b) [10 pts]**
```
v² = v₀² + 2ad
(10)² = (15)² + 2(-2.94)d
100 = 225 - 5.88d
d = 125/5.88 = 21.3 m
```
**Key:** Correct equation (4pts) | Setup (3pts) | Solve (3pts)

**(c) [7 pts]**
```
W = -fd = -μₖmgd
W = -0.3(1200)(9.8)(21.3)
W = -75,254 J

Or: W = ΔKE = ½m(v² - v₀²)
W = ½(1200)(100 - 225) = -75,000 J
```
**Key:** Formula (3pts) | Calculate (3pts) | Units (1pt)

---

## Question 7: Statics & Torque [25 pts]

A uniform 4m beam (50 kg) is supported at both ends. A 30 kg box sits 3m from left end.

**(a)** Draw force diagram. **[5 pts]**
**(b)** Find force at left support. **[12 pts]**
**(c)** Find force at right support. **[8 pts]**

### Solution:

**(a) [5 pts]**
```
Draw horizontal beam:
- Force FL at left end (up)
- Weight 50g at center (2m from left, down)
- Weight 30g at 3m from left (down)
- Force FR at right end (up)
```
**Key:** All forces labeled (3pts) | Distances marked (2pts)

**(b) [12 pts]**
```
Torque about RIGHT end (pivot at right):
Counter-clockwise = Clockwise
FL(4) = 50g(2) + 30g(1)
FL(4) = 50(9.8)(2) + 30(9.8)(1)
FL(4) = 980 + 294 = 1274
FL = 318.5 N
```
**Key:** Choose pivot (2pts) | Write torque equation (4pts) | Distances correct (2pts) | Solve (4pts)

**(c) [8 pts]**
```
ΣFy = 0:
FL + FR = 50g + 30g
318.5 + FR = 50(9.8) + 30(9.8)
318.5 + FR = 784
FR = 465.5 N

Check: 318.5 + 465.5 = 784 ✓
```
**Key:** Write ΣF=0 (2pts) | Setup (3pts) | Solve (2pts) | Check (1pt)

---

## Test Day Essentials

**Always write for every problem:**
1. Diagram (rough is fine)
2. Given values with units
3. Equation before plugging numbers
4. All algebra steps
5. Units on final answer

**Guaranteed partial credit:**
- Free body diagrams with labeled forces
- Conservation laws stated
- Correct equations (even wrong numbers)
- Breaking vectors into components
- Key facts (v=0 at peak, p conserved, etc.)

**Time strategy:**
- 15-20 min/question
- Easy parts first
- Return to hard parts
- 10 min review at end

**Remember:** You need ~30 points to pass. Partial credit adds up fast!

Good luck! 🎯