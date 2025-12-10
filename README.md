# PHYS 140 Final Exam - Practice Test

**Format:** 6-7 questions, 2 hours | **Goal:** Practice writing for partial credit

---

## Question 1: Projectile Motion [25 pts]

A soccer ball is kicked from ground level at an angle of 30° with an initial speed of 25 m/s.

**(a)** What are the x and y components of the initial velocity? **[5 pts]**

**(b)** What is the maximum height the ball reaches? **[8 pts]**

**(c)** How long is the ball in the air? **[7 pts]**

**(d)** How far does the ball travel horizontally? **[5 pts]**

### Solution:

**(a) Components [5 pts]**

**What to write for credit:**
```
Given: v₀ = 25 m/s, θ = 30°

v₀ₓ = v₀ cos(θ) = 25 cos(30°) = 21.7 m/s
v₀ᵧ = v₀ sin(θ) = 25 sin(30°) = 12.5 m/s
```

**Partial credit:** Drawing diagram + writing cos/sin formulas = 2-3 pts

---

**(b) Maximum height [8 pts]**

**What to write for credit:**
```
At max height: vᵧ = 0

Using: vᵧ² = v₀ᵧ² - 2g(y - y₀)
0 = (12.5)² - 2(9.8)(y - 0)
y = 12.5²/(2×9.8) = 156.25/19.6 = 7.97 m
```

**Key for partial credit:**
- State vᵧ = 0 at peak (1 pt)
- Write correct equation (2 pts)
- Plug in numbers with units (2 pts)

---

**(c) Time in air [7 pts]**

**What to write for credit:**
```
Using: y = y₀ + v₀ᵧt - ½gt²
When lands: y = 0

0 = 0 + 12.5t - ½(9.8)t²
4.9t² - 12.5t = 0
t(4.9t - 12.5) = 0
t = 0 or t = 12.5/4.9 = 2.55 s

Answer: t = 2.55 s
```

**Partial credit:** Setup equation with y = 0 (3 pts) | Show algebra (2 pts)

---

**(d) Horizontal range [5 pts]**

**What to write for credit:**
```
x = v₀ₓt = 21.7 × 2.55 = 55.3 m
```

**Partial credit:** Write x = v₀ₓt formula (2 pts)

---

## Question 2: Forces on Incline [25 pts]

A 2.7 kg box sits on a 34° incline. The coefficient of kinetic friction is μₖ = 0.15.

**(a)** Draw free body diagrams for the box. **[6 pts]**

**(b)** If the box slides down, find its acceleration. **[10 pts]**

**(c)** What minimum μₛ would keep the box from sliding? **[9 pts]**

### Solution:

**(a) Free body diagram [6 pts]**

**What to draw for full credit:**
```
[Draw box on incline]
Forces:
- Weight mg pointing straight down
- Normal N perpendicular to surface
- Friction f parallel to surface (up the incline)

Break mg into components:
- mg sin(θ) parallel to incline (down)
- mg cos(θ) perpendicular to incline
```

**Partial credit:** Even rough diagram with labeled forces = 4 pts

---

**(b) Acceleration [10 pts]**

**What to write for credit:**
```
Perpendicular: N - mg cos(θ) = 0
                N = mg cos(θ) = 2.7(9.8)cos(34°) = 21.9 N

Parallel: mg sin(θ) - fₖ = ma
          mg sin(θ) - μₖN = ma
          2.7(9.8)sin(34°) - 0.15(21.9) = 2.7a
          14.8 - 3.29 = 2.7a
          a = 11.5/2.7 = 4.26 m/s²
```

**Key for partial credit:**
- Write N = mg cos(θ) (2 pts)
- Write parallel equation (3 pts)
- Substitute fₖ = μₖN (2 pts)

---

**(c) Minimum μₛ [9 pts]**

**What to write for credit:**
```
For no sliding: a = 0
mg sin(θ) - fₛ = 0
mg sin(θ) = μₛN = μₛmg cos(θ)

μₛ = sin(θ)/cos(θ) = tan(θ)
μₛ = tan(34°) = 0.67
```

**Partial credit:** State a = 0 (2 pts) | Setup equation (3 pts)

---

## Question 3: Energy Conservation [25 pts]

A 100 kg roller coaster starts from rest at height h₁ = 45 m, drops to h₂ = 0 m, then climbs to h₃ = 25 m where it stops. Friction acts between h₂ and h₃ (distance = 25 m).

**(a)** Find gravitational PE at h₁. **[5 pts]**

**(b)** Find speed at h₂. **[8 pts]**

**(c)** Find energy lost to friction. **[12 pts]**

### Solution:

**(a) PE at h₁ [5 pts]**

**What to write for credit:**
```
PE = mgh₁ = 100 × 9.8 × 45 = 44,100 J
```

**Partial credit:** Write PE = mgh (2 pts)

---

**(b) Speed at h₂ [8 pts]**

**What to write for credit:**
```
Energy conservation (no friction A→B):
PE₁ + KE₁ = PE₂ + KE₂
mgh₁ + 0 = 0 + ½mv²

v = √(2gh₁) = √(2 × 9.8 × 45)
v = √882 = 29.7 m/s
```

**Key for partial credit:**
- Write conservation equation (3 pts)
- Cancel mass (1 pt)
- Setup for v (2 pts)

---

**(c) Energy lost [12 pts]**

**What to write for credit:**
```
Energy at B: KE₂ = ½mv² = ½(100)(29.7)² = 44,100 J
Energy at C: PE₃ = mgh₃ = 100(9.8)(25) = 24,500 J

Energy lost = KE₂ - PE₃ 
            = 44,100 - 24,500 = 19,600 J
```

**Partial credit:** State Elost = Einitial - Efinal (4 pts)

---

## Question 4: Circular Motion [25 pts]

A 1000 kg car rounds a flat curve of radius 50 m at 15 m/s.

**(a)** What centripetal force is needed? **[8 pts]**

**(b)** If μₛ = 0.60, will the car make the turn? **[10 pts]**

**(c)** What's the maximum safe speed? **[7 pts]**

### Solution:

**(a) Centripetal force [8 pts]**

**What to write for credit:**
```
Fc = mv²/R = 1000(15)²/50
   = 1000(225)/50 = 4500 N
```

**Partial credit:** Write Fc = mv²/R (3 pts)

---

**(b) Will it make turn? [10 pts]**

**What to write for credit:**
```
Maximum friction: fₘₐₓ = μₛN = μₛmg
                       = 0.60(1000)(9.8) = 5880 N

Since fₘₐₓ (5880 N) > Fc (4500 N):
YES, car will make the turn
```

**Key for partial credit:**
- State friction provides Fc (2 pts)
- Calculate fₘₐₓ = μₛmg (3 pts)
- Compare values (2 pts)

---

**(c) Maximum speed [7 pts]**

**What to write for credit:**
```
At max speed: fₘₐₓ = mv²/R
μₛmg = mv²/R
v = √(μₛgR) = √(0.60 × 9.8 × 50)
v = √294 = 17.1 m/s
```

**Partial credit:** Setup equation μₛmg = mv²/R (4 pts)

---

## Question 5: Momentum & Collision [25 pts]

A 0.15 kg hockey puck moving at 35 m/s is caught by a 70 kg goalie at rest.

**(a)** Find the goalie's recoil velocity. **[12 pts]**

**(b)** How much KE is lost? **[13 pts]**

### Solution:

**(a) Recoil velocity [12 pts]**

**What to write for credit:**
```
Conservation of momentum:
p_before = p_after
m_puck × v_puck + m_goalie × 0 = (m_puck + m_goalie) × v_final

0.15(35) + 0 = (0.15 + 70)v'
5.25 = 70.15v'
v' = 5.25/70.15 = 0.075 m/s
```

**Key for partial credit:**
- Draw before/after diagram (2 pts)
- State momentum conservation (3 pts)
- Write equation (3 pts)
- State "inelastic collision" (1 pt)

---

**(b) Energy lost [13 pts]**

**What to write for credit:**
```
KE_before = ½m_puck v² = ½(0.15)(35)² = 91.875 J

KE_after = ½(m_puck + m_goalie)v'²
         = ½(70.15)(0.075)² = 0.197 J

ΔKE = 91.875 - 0.197 = 91.68 J lost
```

**Partial credit:** Calculate both KE values (5 pts each)

---

## Question 6: Work & Friction [25 pts]

A car's engine shuts off at 15 m/s. It slows to 10 m/s after traveling distance d. The friction coefficient is μₖ = 0.3.

**(a)** Find the deceleration due to friction. **[8 pts]**

**(b)** Find the stopping distance d. **[10 pts]**

**(c)** Calculate work done by friction. **[7 pts]**

### Solution:

**(a) Deceleration [8 pts]**

**What to write for credit:**
```
Friction force: f = μₖmg
Newton's 2nd: f = ma
μₖmg = ma
a = μₖg = 0.3(9.8) = 2.94 m/s²

(negative since it opposes motion)
a = -2.94 m/s²
```

**Partial credit:** Write f = μₖmg (2 pts) | State a = μₖg (3 pts)

---

**(b) Distance d [10 pts]**

**What to write for credit:**
```
Using: v² = v₀² + 2ad
(10)² = (15)² + 2(-2.94)d
100 = 225 - 5.88d
5.88d = 125
d = 21.3 m
```

**Partial credit:** Write correct kinematic equation (4 pts)

---

**(c) Work by friction [7 pts]**

**What to write for credit:**
```
W = -f × d = -μₖmg × d
(negative because friction opposes motion)

Or using energy:
W = ΔKE = ½m(v² - v₀²) = ½m(100 - 225)
W = -62.5m (depends on mass, which wasn't given)
```

**Partial credit:** Write W = fd or W = ΔKE (3 pts)

---

## Question 7: Statics & Torque [25 pts]

A uniform 50 kg beam (length 4 m) is supported at its left end. A 30 kg box sits 3 m from the left end.

**(a)** Draw diagram showing all forces. **[5 pts]**

**(b)** Find the support force at left end. **[12 pts]**

**(c)** Where should a 20 kg box be placed to balance? **[8 pts]**

### Solution:

**(a) Diagram [5 pts]**

**What to draw for credit:**
```
[Draw horizontal beam]
- Support force F_support at left (up)
- Weight of beam: 50g at center (2 m from left)
- Weight of box: 30g at 3 m from left
```

**Partial credit:** Label pivot and forces (3 pts)

---

**(b) Support force [12 pts]**

**What to write for credit:**
```
Torque about left end (pivot):
Counter-clockwise = Clockwise

0 = (50g)(2) + (30g)(3)
(Note: support force creates no torque at pivot)

Wait - this doesn't balance! Need reaction at right end too.
Actually, this is a simple support problem:

ΣF_y = 0:
F_support - 50g - 30g = 0
F_support = 80g = 80(9.8) = 784 N
```

**Partial credit:** Write ΣF = 0 (4 pts) | Setup equation (4 pts)

---

**(c) Balancing position [8 pts]**

**What to write for credit:**
```
Need more info about pivot location or additional support.
If balanced on pivot at some point x:
Torques must balance about pivot point.

For seesaw at center (2 m):
Left side: 50g(0) + weight at distance d_left
Right side: 30g(1)

Show setup even if can't complete!
```

**Partial credit:** State Στ = 0 (3 pts) | Attempt setup (3 pts)

---

## Key Takeaways for Test Day

**Always write:**
1. **Diagram** (even rough) - shows you understand
2. **Given values** with units
3. **Relevant equation** - gets partial credit
4. **Setup before numbers** - shows process
5. **Units on answer** - easy points

**Partial credit gold:**
- Free body diagrams
- Conservation statements
- Identifying forces/components
- Writing equations (even if wrong numbers)
- Stating key facts (v=0 at peak, momentum conserved, etc.)

**Time management:**
- 15-20 min per question
- Do easiest parts first
- Circle back to hard parts
- Check units on everything

---

Good luck! 🎯