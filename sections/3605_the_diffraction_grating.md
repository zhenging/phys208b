---
tags: []
---

### 3605 The Diffraction Grating
An array of a large number of parallel slits, all with the same width *a* and spaced equal distances *d* between centers, is called a **diffraction grating**.

**Intensity maxima multiple slits**
$$
d\sin\th = m \lambda \quad (m = 0, \pm 1, \pm 2, \cdots) \quad\bold{(36.13)}
$$
$d$ - Distance between slits
$\th$ - Angle of line from center of the slit array to *m*th bright region on screen
$\lambda$ - Wavelength

#### Examples
The wavelengths of the visible spectrum are approximately 380 nm (violet) to 750 nm (red). (a) Find the angular limits of the firstorder visible spectrum produced by a plane grating with 600 slits per millimeter when white light falls normally on the grating. (b) Do the first-order and second-order spectra overlap? What about the second-order and third-order spectra? Do your answers depend on the grating spacing?
>Solution
We must find the angles spanned by the visible specttrum in the first-, second-, and third-order spectra. Thest correspond to m=1, 2, and 3 in Eq.(36.13).
a. The grating spacing is
$$
\begin{aligned}
d= \frac{1}{600 \text{ slits/mm}} = 1.67 \times 10^{-6} \text{ m}
\end{aligned}
$$
Solve for $\th$
$$
\begin{aligned}
\th &= \arcsin \frac{m \lambda}{d}
\end{aligned}
$$
Then for m=1, the angle deviation $\th_{v1}$ and $\th_{r1}$ for violet and red light, respectively, are
$$
\begin{aligned}
\th_{v1} &= \arcsin(\frac{3.8 \times 10^{-7}}{1.67 \times 10^{-6}}) = 13.2\degree\\
\th_{r1} &= \arcsin(\frac{7.5 \times 10^{-7}}{1.67 \times 10^{-6}}) = 26.7\degree
\end{aligned}
$$
When m = 2 and 3, our equation $\th = \arcsin(m \lambda/d)$ for violet light and red light yields
$$
\begin{aligned}
\th_{v2} &= \arcsin(2\frac{3.8 \times 10^{-7}}{1.67 \times 10^{-6}}) = 27.1\degree\\
\th_{r2} &= \arcsin(2\frac{7.5 \times 10^{-7}}{1.67 \times 10^{-6}}) = 63.9\degree\\
\th_{v3} &= \arcsin(3\frac{3.8 \times 10^{-7}}{1.67 \times 10^{-6}}) = 43.0\degree\\
\th_{r3} &= \arcsin(3\frac{7.5 \times 10^{-7}}{1.67 \times 10^{-6}}) = \arcsin(1.35) = \text{undefined}
\end{aligned}
$$
Hence the second-order spectrum extends from $27.1\degree$ to $63.9\degree$ and the third-order spectrum extends from $43.0\degree$ to $90
\degree$ (the largest possible value of u). The undefined value of ur3 means that the third-order spectrum reaches $u = 90\degree= \arcsin(1)$ at a wavelength shorter than 750 nm; you should be able to show that this happens for $\lambda = 557$ nm. Hence the first-order spectrum (from $13.2\degree$ to $26.7\degree$) does not overlap with the second-order spectrum, but the second- and third-order spectra do overlap. You can convince yourself that this is true for any value of the grating spacing *d*.

#### Exercises
23, 24, 26, 28, 59

36.23 When laser light of wavelength 632.8 nm passes through a diffraction grating, the first bright spots occur at $\pm 17.8\degree$ from the central maximum.
(a) What is the line density (in lines/cm) of this grating?
(b) How many additional bright spots are there beyond the first bright spots, and at what angles do they occur?
>Solution
a. The line density is 4830 lines/cm.
$$
\begin{aligned}
d\sin\th &= m \lambda\\
\th &= 17.8\degree, m = 1, \lambda = 6.328 \times 10^{-7}\text{m}\\
\To d &= \frac{m \lambda}{\sin\th}\\
&= \frac{1 \times 6.328 \times 10^{-7}\text{m}}{\sin{17.8\degree}} = 2.07\times 10^{-4} \text{cm}\\
\frac{1\text{cm}}{d} &= 4830\text{ lines/cm}
\end{aligned}
$$
b. There are two additional bright spots beyond the first one. And their angles are as follows
$$
\begin{aligned}
m &= 2 \To \th_2 = \arcsin \frac{2 \lambda}{d} = 37.7\degree\\
m &= 3 \To \th_3 = \arcsin \frac{3 \lambda}{d} = 66.5\degree\\
m &= 4 \To \th_4 = \arcsin \frac{4 \lambda}{d} = \text{undefined}
\end{aligned}
$$

36.24 Monochromatic light is at normal incidence on a plane transmission grating. The first-order maximum in the interference pattern is at an angle of $11.3\degree$. What is the angular position of the fourth-order maximum?
>Solution
$\th = \arcsin(\dfrac{4 \lambda}{d})$ and $\arcsin(\dfrac{\lambda}{d}) = 11.3 \degree$. $\th = 51.6\degree$

36.26 If a diffraction grating produces a third-order bright spot for red light (of wavelength 700 nm) at $65.0\degree$ from the central maximum, at what angle will the second-order bright spot be for violet light (of wavelength 400 nm)?
>Solution
Todo

36.28 . The wavelength range of the visible spectrum is approximately 380–750 nm. White light falls at normal incidence on a diffraction grating that has 350 slits/mm. Find the angular width of the visible spectrum in (a) the first order and (b) the third order. (Note: An advantage of working in higher orders is the greater angular spread and better resolution. A disadvantage is the overlapping of different orders, as shown in Example 36.4.)
>Solution
Todo

36.59 A diffraction grating has 650 slits/mm. What is the highest order that contains the entire visible spectrum? (The wavelength range of the visible spectrum is approximately 400-700 nm.)
>Solution
Second-order.
$$
\begin{aligned}
d\sin\th &= m \lambda\\
\th &= \arcsin \frac{m \lambda}{d}\\
d &= \frac{10^{-3}}{650} \text{m}\\
\lambda_1 &= 4 \times 10^{-7} \text{m}\\
\lambda_2 &= 7 \times 10^{-7} \text{m}\\
m &= 2 \To \th_1 = 31.3 \degree , \th_2 = 65.5\degree\\
m &= 3 \To \th_1 = 51.3 \degree , \th_2 = \text{undefined}
\end{aligned}
$$
Therefore, the highest order that contains the entire visible specturm is second-order.
