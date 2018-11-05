---
tags: []
---

### 2403 Energy Storage in Capacitors
Let $q$ and $v$ be the charge and potential differencem respectively, at an intermediate stage during the charging processing, then $v =q/c$. At this stage the work $dW$ required to transfer an additional element of charge $dq$ is
$$
\begin{aligned}
dW = v dq = \frac{qdq}{C}
\end{aligned}
$$
The total work $W$ needed to increase the capacitor charge $q$ from zero to Q is
$$
\begin{aligned}
W = \int_0^W dW = \frac{1}{C}\int_0^Q qdq = \frac{Q^2}{2C} \quad\bold{(24.8)}
\end{aligned}
$$
We defined the potential energy if an uncharged capacitor to be zero, then $W$ in Eq. (24.8) is equal to the potential energy $U$ of the charged capacitor. The final stored charge is $Q = CV$, so we can express $U$ (which is equal to $W$) as
$$
\begin{aligned}
U = \frac{Q^2}{2C} = \frac{1}{2}CV^2 = \frac{1}{2}QV \quad\bold{(24.9)}
\end{aligned}
$$

#### Electric-Field Energy
The stored potential energy is $\frac{1}{2}CV^2$ and the volume between the plates is $Ad$; hence
$$
\begin{aligned}
u = \text{Energy density} = \frac{\frac{1}{2}CV^2}{Ad} = \frac{1}{2}\epsilon_0 E^2 \quad\bold{(24.11)}
\end{aligned}
$$

#### Exercises
23, 27

24.23 A $5.80 \mu F$, parallel-plate, air capacitor has a plate separation of 5.00 mm and is charged to a potential difference of 400 V. Calculate the energy density in the region between the plates, in units of $J/m^3$.
>Solution
The electric field
$$
\begin{aligned}
E &= \frac{V_{ab}}{d} = \frac{400}{5 \times 10^{-3}} = 8 \times 10^4 V/m
\end{aligned}
$$
The energy density is
$$
\begin{aligned}
u &= \frac{1}{2}\epsilon_0 E^2 = \frac{1}{2} \times 8.85 \times 10^{-12} \times (8 \times 10^4)^2\\
&= 0.0283 J/m^3
\end{aligned}
$$

24.27 You have two identical capacitors and an external potential source. (a) Compare the total energy stored in the capacitors when they are connected to the applied potential in series and in parallel. (b) Compare the maximum amount of charge stored in each case. (c) Energy storage in a capacitor can be limited by the maximum electric field between the plates. What is the ratio of the electric field for the series and parallel combinations?
>Solution
Let the capacitance of each capacitor be $C$, and the potential difference of the source be $V$.
**Parallel**:
$$
\begin{aligned}
V_1 &= V_2 = V\\
Q_{total} &= CV_1 + CV_2 = 2CV\\
U_{total} &= \frac{1}{2}CV^2 + \frac{1}{2} CV^2 = CV^2\\
E &= \frac{V_1}{d} = \frac{V}{d}
\end{aligned}
$$
**Series**:
$$
\begin{aligned}
V_1 &= V_2 = \frac{1}{2}V\\
Q_{total} &= C V_1 + C V_2 = CV\\
U_{total} &= \frac{1}{2}CV_1^2 + \frac{1}{2}CV_2^2 = \frac{1}{4}CV^2\\
E &= \frac{V_1}{d} = \frac{V}{2d}
\end{aligned}
$$
