---
tags: []
---

### 2105 Electric Field Calculations

#### Example 21.9 Field of A Ring of Charge
Charge Q is uniformly distributed around a conducting ring of radius a (Fig. 21.23). Find the electric field at a point P on the ring axis at a distance x from its center.
![Graph](../assets/21_23.png)
>Solution
$E = \dfrac{kQx}{(a^2 + x^2)^{\frac{3}{2}}} \hat i$

#### Example 21.11 Field of A Uniformly Charged Disk
A nonconducting disk of radius R has a uniform positive surface charge density s. Find the electric field at a point along the axis of the disk a distance x from its center. Assume that x is positive.
![Graph](../assets/21_25.png)

#### Example 21.12 Field of Two Oppositely Charged Infinite Sheets
Two infinite plane sheets with uniform surface charge densities $+\sigma$ and $-\sigma$  are placed parallel to each other with separation d(Fig. 21.26). Find the electric field between the sheets, above the upper sheet, and below the lower sheet.
![Graph](../assets/21_26.png)

#### Exercises
36, 38, 42, 43, 62, 65, 79, 82, 85, 86, 88

21.36 Two point charges Q and +q (where q is positive) produce the net electric field shown at point P in Fig. E21.36. The field points parallel to the line connecting the two charges.
(a) What can you conclude about the sign and magnitude of Q? Explain your reasoning.
(b) If the lower charge were negative instead, would it be possible for the  field to have the direction shown in the figure? Explain your reasoning.

21.38 The two charges $q_1$ and Figure E21.38 $q_2$ shown in Fig. E21.38 have equal magnitudes. What is the direction of the net electric field due to these two charges at points A (midway between the charges), B, and C if (a) both charges are negative, (b) both charges are positive, (c) $q_1$ is positive and $q_2$ is negative.

21.79 Positive charge Q is distributed uniformly along the x-axis from $x = 0$ to $x = a$. A positive point charge q is located on the positive x-axis at $x = a + r$, a distance $r$ to the right of the end of Q (Fig. P21.79).
(a) Calculate the x- and y-components of the electric field produced by the charge distribution Q at points on the positive x-axis where $x > a$.
(b) Calculate the force (magnitude and direction) that the charge distribution Q exerts on q.
(c) Show that if $r >> a$, the magnitude of the force in part (b) is approximately $Qq /4\pi \epsilon_0 r^2$. Explain why this result is obtained.
![Graph](../assets/21_79.png)
>Solution
a. Let the charge density be $\lm = \dfrac{Q}{a}$. At point x, the y-component of electric field is zero, and the x-component of electric field is the electri field produced by $dQ$ of the charge distribution Q.
$$
\begin{aligned}
dQ &= \lm dx\\
dE_x &= \frac{k dQ}{(a+r-x)^2} = \frac{k \lm dx}{(a+r-x)^2}\\
E_x &= k \lm \int_0^a \frac{dx}{(a+r-x)^2}\\
&= k \lm \bigg(\frac{1}{a+r-x}\bigg) \bigg\vert_0^a\\
&= \frac{k \lm \cdot a}{r(a+r)}\\
&= \frac{k Q}{r(a+r)}\\
E &= E_x \hat i = \frac{k Q}{r(a+r)} \hat i
\end{aligned}
$$
b. The electric force $\vec F = Eq = \dfrac{k Qq}{r(a+r)} \hat i$. The direction is +x-axis.
c. When $r >> a$,
$$
\begin{aligned}
r(a+r) &\approx r^2\\
F &= \frac{k Qq}{r(a+r)} \\
&=\frac{k Qq}{r^2} = \frac{Qq}{4\pi \epsilon_0 r^2}
\end{aligned}
$$

21.82 Positive charge Q is distributed uniformly along the positive y-axis between $y = 0$ and $y = a$. A negative point charge $-q$ lies on the positive Q x-axis, a distance $x$ from the origin.
(a) Calculate the x- and y-components of the electric field produced by the charge distribution Q at points on the positive x-axis.
(b) Calculate the x- and y-components of the force that the charge distribution Q exerts on q.
(c) Show that if $x >> a$, $F_x \approxeq \dfrac{-Qq}{4\pi\epsilon_0 x^2}$ and $F_y \approxeq \dfrac{+Qqa}{8\pi\epsilon_0 x^3}$. Explain why this result is obtained.
![Graph](../assets/21_82.png)
>Solution
Let the charge density be $\lm = Q/a$, we have $dQ = \lm \cdot dy$
The x-component of the electric field is
$$
\begin{aligned}
dE_x &= \frac{kdQ}{r^2} \cos \th\\
&= k \lm dy \cdot \frac{1}{x^2 + y^2} \cdot \frac{x}{\sqrt{x^2 + y^2}}\\
&= k \lm x\cdot \frac{1}{(x^2 + y^2)^{\frac{3}{2}}}\cdot dy\\
E_x &= k\lm x \int_0^a \frac{1}{(x^2 + y^2)^{\frac{3}{2}}}dy\\
&= \frac{kQx}{a} \big(\frac{y}{x^2\sqrt{x^2 + y^2}}\big)\big\vert_0^a\\
&= \frac{kQ}{x\sqrt{x^2 + a^2}}
\end{aligned}
$$
The y-component of the electric field is
$$
\begin{aligned}
dE_y &= \frac{kdQ}{r^2} \sin \th\\
&= k \lm dy \cdot \frac{1}{x^2 + y^2} \cdot \frac{y}{\sqrt{x^2 + y^2}}\\
&= k \lm \cdot \frac{y}{(x^2 + y^2)^{\frac{3}{2}}}\cdot dy\\
E_y &= k\lm \int_0^a \frac{y}{(x^2 + y^2)^{\frac{3}{2}}}dy\\
&= \frac{kQ}{a} \big(-\frac{1}{\sqrt{x^2 + y^2}}\big)\big\vert_0^a\\
&= \frac{kQ}{a} \big( \frac{1}{x} - \frac{1}{\sqrt{x^2 + a^2}}\big)
\end{aligned}
$$
c. Hint: $(1 + z)^n = 1 + nz + \cdots$
$$
\begin{aligned}
\frac{1}{\sqrt{x^2 + a^2}} &= \frac{1}{x} (1-\frac{a^2}{2x^2})\\
F_x = - E_x q &= \frac{kQ}{x\sqrt{x^2 + a^2}}\\
&=-\frac{kQ}{x^2}(1-\underbrace{\frac{a^2}{2x^2}}_{\blue{approaches 0}})\\
&=-\frac{kQ}{x^2} = \frac{-Qq}{4\pi\epsilon_0 x^2}\\
F_y = E_y q &= \frac{kQq}{a} \big( \frac{1}{x} - \frac{1}{\sqrt{x^2 + a^2}}\big)\\
&= \frac{kQ}{a} \cdot \frac{1}{x} \big(1 - 1 + \frac{a^2}{2x^2}\big)\\
&= \frac{kQa}{2x^3} =\frac{+Qqa}{8\pi\epsilon_0 x^3}
\end{aligned}
$$

21.85 Negative charge $-Q$ is distributed uniformly around a quarter-circle of radius $a$ that lies in the first quadrant, with the center of curvature at the origin. Find the x- and y-components of the net electric field at the origin.
![Graph](../assets/21_85.png)
>Solution
Let the magnitude of the charge density be $\d\lm = \frac{Q}{a\cdot \frac{\pi}{2}} = \frac{2Q}{\pi a}$.
$$
dQ = \lm \cdot a d\th = \frac{2Q}{\pi}d\th
$$
The x-component of the electri field is
$$
\begin{aligned}
dE_x &= \frac{k dQ}{a^2} \cos \th\\
E_x &= \frac{k}{a^2} \cdot \frac{2Q}{\pi} \int_0^{\pi/2} \cos \th d\th\\
&= \frac{2kQ}{\pi a^2} (\sin \th) \big\vert_0^{\pi/2}\\
&= \frac{2kQ}{\pi a^2}
\end{aligned}
$$
The y-component of the electri field is
$$
\begin{aligned}
dE_y &= \frac{k dQ}{a^2} \sin \th\\
E_y &= \frac{k}{a^2} \cdot \frac{2Q}{\pi} \int_0^{\pi/2} \sin \th d\th\\
&= \frac{2kQ}{\pi a^2} (-\cos \th) \big\vert_0^{\pi/2}\\
&= \frac{2kQ}{\pi a^2}
\end{aligned}
$$

21.86 A semicircle of radius $a$ is in the first and second quadrants, with the center of curvature at the origin. Positive charge $+Q$ is distributed uniformly around the left half of the semicircle, and negative charge $-Q$ is distributed uniformly around the right half of the semicircle (Fig. P21.86). What are the magnitude and direction of the net electric field at the origin produced by this distribution of charge?
![Graph](../assets/21_86.png)
>Solution
Let the electric field of positive charge be $E_1$, and that of negative charge be $E_2$. From (21.85), we know that
$$
\begin{aligned}
E_1 &= \frac{2kQ}{\pi a^2} \ihat -\frac{2kQ}{\pi a^2} \jhat\\
E_2 &= \frac{2kQ}{\pi a^2} \ihat +\frac{2kQ}{\pi a^2} \jhat\\
E_{total} &= E_1 + E_2\\
&= \frac{4kQ}{\pi a^2} \ihat
\end{aligned}
$$
