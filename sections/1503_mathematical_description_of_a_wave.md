---
tags: []
---

### 1503 Mathematical Description of a Wave
#### Wave Function
Waves on a string are transverse; during wave motion a particle with equilirum position $x$ is displaced some distance $y$ in the direction perpendicular to the x-axis. The value of $y$ depends on which particle we are takling about ($x$), and also on the time $t$. Thus $y$ is a function of both $x$ and $t$.
$$
\begin{aligned}
y = y(x, t)
\end{aligned}
$$

#### Wave Function for a Sinusoidal Wave
Suppose that the displacement of a particle at the left end of the string ($x=0$), where the wave originates, is given by
$$
\begin{aligned}
y(x=0, t) = A\cos(\omega t) = A \cos(2\pi f t) \quad \bold{(15.2)}
\end{aligned}
$$
The wave disturbance traves from $x=0$ to some point x to the right of the origin in an mount of time given by $\dfrac{x}{v}$, where $v$ is the wave speed. So the motion of point $x$ at time $t$ is the same at the motion of point $x=0$ at the earlier time $(t-\dfrac{x}{v})$. Hence we can find the displacement of point $x$ at time $t$ by simpley replacing $t$ in Eq. (15.2) by $(t-\dfrac{x}{v})$.
$$
\begin{aligned}
y(x, t) = A\cos\lb \omega (t - \frac{x}{v})\rb
\end{aligned}
$$
Because $\cos \th = \cos(-\th)$, we can rewrite the wave function as
$$
\begin{aligned}
y(x, t) = A\cos\lb \omega (\frac{x}{v} - t)\rb
\end{aligned} \quad \bold{(15.3)}
$$
$y$ - Wave function form a sinusoidal wave propagating;
$A$ - Amplitude
$\omega$ - Angular frequency = $2\pi f$
$v$ - Wave speed
$x$ - Position
$t$ - Time

Express Eq. (15.3) in terms of period $T=1/f$ and the wavenlength $\lambda = v/f = \frac{2\pi v}{\omega}$:
$$
\begin{aligned}
y(x, t) = A\cos\lb 2\pi (\frac{x}{\lambda} - \frac{t}{T})\rb
\end{aligned} \quad \bold{(15.4)}
$$

Let $k = \frac{2\pi}{\lambda}$ (called **wave number**), we have $\lambda = 2\pi k$. We can then rewrite Eq. (15.4) as
$$
\begin{aligned}
y(x, t) = A\cos(kx - \omega t)
\end{aligned} \quad \bold{(15.7)}
$$

#### More on the Wave Function
For a wave travelling in the **negative** x-direction,
$$
\begin{aligned}
y(x, t) = A\cos\lb \omega (\frac{x}{v} + t)\rb =  A\cos\lb 2\pi (\frac{x}{\lambda} + \frac{t}{T})\rb = A\cos(kx + \omega t) \quad \bold{(15.8)}
\end{aligned}
$$

#### Particial Velocity and Acceleration in a Sinusoidal Wave
Waven equation involves second partial derivatives of wave function
$$
\begin{aligned}
\frac{\partial^2y(x, t)}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y(x, t)}{\partial t^2} \quad \bold{(15.12)}
\end{aligned}
$$


#### Exercises
7, 8, 9, 10, 11, 12

15.7 Transverse waves on a string have wave speed 8.00 m/s, amplitude 0.0700 m, and wavelength 0.320 m. The waves travel in the −x-direction, and at t = 0 the x = 0 end of the string has its maximum upward displacement.
(a) Find the frequency, period, and wave number of these waves.
(b) Write a wave function describing the wave.
(c) Find the transverse displacement of a particle at $x = 0.360$ m at time $t = 0.150$ s.
(d) How much time must elapse from the instant in part (c) until the particle at x = 0.360 m next has maximum upward displacement?
>Solution
a. Frequency $f = \dfrac{v}{\lambda} = \frac{8}{0.32} = 25 \text{Hz}$
Period $T = \dfrac{1}{f} = 0.04s$
Wave number $k = \dfrac{2\pi}{\lambda} = \dfrac{2\pi}{0.32} = 6.25 \pi \text{ rad/m}$
b. Waven function. (negative x-axis)
$$
\begin{aligned}
y(x, t) &= A \cos(kx + \omega t)\\
&= 0.07 \cos(6.25 \pi x + 2\pi \times 25 t)\\
&= 0.07 \cos(6.25 \pi x + 50\pi t)
\end{aligned}
$$
c. $x = 0.360$ m at time $t = 0.150$ s
$$
\begin{aligned}
y(x, t) &= 0.07 \cos(6.25 \pi \times 0.36 + 50\pi \times 0.15)\\
&= 0.0495 \text{ m}
\end{aligned}
$$
d. $y = 0.07 \text{m}, x=0.360 \text{ m}$
$$
\begin{aligned}
y(x, t) &= 0.07 \cos(6.25 \pi x + 50\pi t)\\
0.07 &= 0.07 \cos(6.25 \pi \times 0.36 + 50 \pi t)\\
\To t &= 0.035 + nT\text{ s}\\
t &\gt 0.15\\
\To &n > 2.875 \\
\Delta t = 0.035 + 3 \times 0.04 - 0.15 = 0.005 \text{s}
\end{aligned}
$$
The moment $y$ has the maximum upward displacement after $t=0.15 \text{s}$ is when $n = 3$, and the time elapsed is $0.005$ s.

15.8 A certain transverse wave is described by
$$
y(x, t) = (6.50 \text{ mm}) \cos{2\pi (\frac{x}{28.0 \text{ cm}} - \frac{t}{0.0360 \text{ s}})}
$$
Determine the wave’s (a) amplitude; (b) wavelength; (c) frequency; (d) speed of propagation; (e) direction of propagation.
>Solution
Amplitude, $A = 6.50 \text{ mm}$
Wavelength, $\lambda = 28.0 \text{ cm} = 0.28 \text{ m}$
Frequency, $f = \dfrac{1}{T} = \dfrac{1}{0.036 \text{ s}} = 27.8 \text{ Hz}$
Speed of propagtion, $v = \lambda f = 0.28 \times 27.8 = 7.8 \text{ m/s}$
Direction of progation, **positive** x-direction.

15.9 **CALC** Which of the following wave functions satisfies the wave equation, Eq. (15.12)? (a) $y(x, t) = A(\cos{kx + \omega t})$; (b) $y(x, t) = A(\sin{kx + \omega t})$; (c) $y(x, t) = A(\cos{kx} + \cos{\omega t})$. (d) For the wave of part (b), write the equations for the transverse velocity and transverse acceleration of a particle at point x.
>Solution
Todo

15.10 A water wave traveling in a straight line on a lake is described by the equation
$$
y(x, t) = (2.75 \text{ cm}) \cos(0.410 \text{ rad/cm x} + 6.20 \text{rad/s t})
$$
where $y$ is the displacement perpendicular to the undisturbed surface of the lake.
(a) How much time does it take for one completewave pattern to go past a fisherman in a boat at anchor, and what horizontal distance does the wave crest travel in that time?
(b) What are the wave number and the number of waves per second that pass the fisherman?
(c) How fast does a wave crest travel past the fisherman, and what is the maximum speed of his cork floater as the wave causes it to bob up and down?
>Solution
$$
\begin{aligned}
\omega &= 6.20 \text{ rad/s} = 6.20 \times \frac{\pi}{180} \text{s}^{-1}\\
T  &= \dfrac{2\pi}{\omega} = \dfrac{2\pi}{ 6.2 \times \frac{\pi}{180}} = 58.1 \text{ s}\\
k = & 0.410 \text{ rad/cm} = 41 \times \frac{\pi}{180} \text{m}^{-1}\\
\lambda &= \dfrac{2\pi}{k} = \dfrac{2\pi}{41 \times \frac{\pi}{180}} = 8.78 \text{ m}\\
f &= \frac{1}{T} = 0.0172 \text{ Hz}\\
v &= \lambda f = 8.78 \times 0.0172 = 0.15m/s
\end{aligned}
$$

15.11 A sinusoidal wave is propagating along a stretched string that lies along the x-axis. The displacement of the string as a function of time is graphed in Fig. E15.11 for particles at $x=0$ and $x=0.0900$ m.
(a) What is the amplitude of the wave?
(b) What is the period of the wave?
(c) You are told that the two points x = 0 and x = 0.0900 m are within one wavelength of each other. If the wave is moving in the + xdirection, determine the wavelength and the wave speed.
(d) If instead the wave is moving in the - x-direction, determine the wavelength and the wave speed.
(e) Would it be possible to determine definitively the wavelengths in parts (c) and (d) if you were not told that the two points were within one wavelength of each other? Why or why not?
![Graph](../assets/15_11.png)
>Solution
Amplitude $A = 4 \text{ mm}$, Period $T = 0.04s$
c. When the wave travels in the positive x-axis, the time elasped from $x=0$ to $x=0.09$ is $\Delta t=0.035-0.01 = 0.025s$.
$$
\begin{aligned}
v &= \frac{\Delta x}{\Delta t} = \frac{0.09}{0.025} = 3.6 \text{ m/s}\\
\lambda &= vT = 3.6 \times 0.04 = 0.144 \text{ m}
\end{aligned}
$$
d. When the wave travels in the negative x-axis, the time elasped from $x=0$ to $x=0.09$ is $\Delta t=0.05 - 0.035 = 0.015s$.
$$
\begin{aligned}
v &= \frac{\Delta x}{\Delta t} = \frac{0.09}{0.015} = 6 \text{ m/s}\\
\lambda &= vT = 6 \times 0.04 = 0.24 \text{ m}
\end{aligned}
$$
e. It is impossible. The possibility of the number of waves between these two points is infinite.

15.12 **CALC** Speed of Propagation vs. Particle Speed.
(a) Show that Eq. (15.3) may be written as $y(x, t) = A\cos\lb \dfrac{2\pi}{\lambda} (x-vt)\rb$.
(b) Use $y(x, t)$ to find an expression for the transverse velocity $v_y$ of a particle in the string on which the wave travels.
(c) Find the maximum speed of a particle of the string. Under what circumstances is this equal to the propagation speed $v$? Less than $v$? Greater than $v$?
>Solution
a.
$$
\begin{aligned}
y(x, t) &= A\cos\lb \omega (\frac{x}{v} - t)\rb\\
y(x, t) &= A\cos\lb \frac{2\pi}{T} (\frac{x}{v} - t)\rb\\
y(x, t) &= A\cos\lb \frac{2\pi}{vT} (x - vt)\rb\\
y(x, t) &= A\cos\lb \frac{2\pi}{\lambda} (x - vt)\rb\\
\end{aligned}
$$
b. Todo
