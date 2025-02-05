# Section A

## <ins>Question 1</ins>
[Maximum rank: 6]<br>
The functions $f$ and $g$ are both defined for $-1 \leq x \leq 0$ by <br>
```math
f(x) = 1 - x^2
```
```math
g(x) = e^{2x}
```
The graphs of $f$ and $g$ intersect at $x=a$ and $x=b$, where $a<b$. <br>
**(a) Find the value of $a$ and the value of $b$.** <br>
<details>
  <summary>Answer</summary>
  $f(x) = g(x)$<br>
  $1-x^2 = e^{2x}$<br>
  Using GDC:<br>
  $b = -0.917$<br>
  $a = 0$
</details>

**(b) Find the area of the region enclosed by the graphs of $$f$$ and $g$.**
<details>
  <summary>Answer</summary>
  $A = \int^a_b g(x) - f(x) dx$ <br><br>
  $A = \int^{0}_{-0.917} |1-x^2-e^{2x}| dx$ <br><br>
  $= x-\frac{1}{3}x^3-\frac{1}{2}e^{2x} \Big|^0_{-0.917}$
</details>

## <ins>Question 7</ins>
[Maximum mark: 5]
The curve $y = 4\ln(x-2)$ for $0\leq y \leq 4$ is rotated $360º$ about the $y$-axis to form a solid of revolution.

Find the volume of the solid formed.

<details>
  <summary>Answer</summary>
  Put $x$ in terms of $y$  <br>
  $y = 4\ln(x-2)$ <br>
</details>

## <ins>Question 8</ins>
[Maximum mark: 10]

Let $z = 1 +\cos 2\theta + i \sin 2\theta$, where $-\frac{\pi}{2} < \theta < \frac{\pi}{2}$. <br>
(a) Show that <br>
  (i) $\arg z = \theta$ <br>
  (ii) $|z| = 2 \cos \theta$.<br>

(b) Hence or otherwise, find the value of $\theta$ such that $\arg(z^2) = |z^3|$.

## <ins>Question 12</ins>
[Maximum mark: 21]
Consider the differential equation $\dfrac{dy}{dx} - y\csc 2x = \sqrt{\tan x}$, where $0 < x < \dfrac{\pi}{2}$ and $y = \dfrac{\pi}{4}$ at $x = \dfrac{\pi}{4}$.

(a) Use Euler's method with step length $\dfrac{\pi}{12}$ to find an approximate value of $y$ when $x = \dfrac{5\pi}{12}$. <br>
Give your answer correct to three significant figures.<br>

(b) Show that $\dfrac{d}{dx}(\dfrac{1}{2}\ln(\cot x)) = -2 \csc 2x$.

(c) Show that $\sqrt{\cot x}$ is an integrating factor for this differential equation. 

(d) Hence, by solving the differential equation, show that $y = x\sqrt{\tan x}$.

(e) Consider the curve $y = x \sqrt{\tan x}$ for 

