**Average Velocity Formula :** 
$$v_{av} = \frac{s(t_1) - s(t_0)}{t_1 - t_0}$$
- _The average velocity is simply the slope function of the line joining two examined points._
- The average velocity is the change in position divided by the change in time.
- Any such line joining points such as this is referred to as a **secant line**. The slope of such is the average velocity.

As for finding the instantaneous velocity of an object, we can use the following formula over smaller and smaller intervals $[\;1, t\;]$ in order to reasonably estimate the instantaneous velocity as the output approaches a value.

_**NOTE** : Usage of 1 in the following equations is simply a placeholder, the instantaneous velocity is simply t approaching a value, 1 in this case, however it can approach any in real cases._

**Instantaneous Velocity :**
$$v_{av} = \frac{s(t) - s(1)}{t - 1}$$
	 To form a better definition of this, we say that the limit of $v_{av}$ as $t$ approaches 1 equals the instantaneous velocity $v_{inst}$ , represented by the following statement :
$$v_{inst} = \lim_{t \to 1} v_{av} = \lim_{t \to 1} \frac{s(t) - s(1)}{t - 1}$$
- Just as average velocities approach a limit as $t$ approaches 1, the slopes of the secant lines approach the same limit as $t$ approaches 1; more specifically the following two things happen :
	- The secant lines approach the **tangent line** of the point on the curve.
	- The slopes of the secant lines $m_{sec}$ approach the slope of the tangent line $m_{tan}$ at the point $(1, \;s(1))$ .
- Therefore, the slope of the tangent line is also expressed as a limit, the same that defines the instantaneous velocity.

**Two-Sided Limit :**
	Suppose the function $f$ is defined for all $x$ near $a$ except possibly at $a$. If $f(x)$ is arbitrarily close to $L$ (as close to $L$ as we like) for all $x$ sufficiently close (but not equal) to $a$, we write:
$$\lim_{x \to a}f(x) = L$$
	and say the limit of $f(x)$ as $x$ approaches $a$ equals $L$.

- The value of $\lim_{x \to a}f(x)$ (if it exists) depends on the values of $f$ near $a$, but it does not depend on the value of $f(a)$. In some cases, the limit $\lim_{x \to a}f(x)$ equals $f(a)$. In other instances, $\lim_{x \to a}f(x)$ and $f(a)$ differ, or $f(a)$ may not even be defined.

**Right-Sided Limit :**
	Suppose $f$ is sufficiently defined for all $x$ near $a$ with $x > a$. If $f(x)$ is arbitrarily close to $L$ for all $x$ sufficiently close to $a$ with $x > a$, we write:
$$\lim_{x \to a^+}f(x) = L$$
	and say the limit of $f(x)$ as $x$ approaches $a$ from the right equals $L$.

**Left-Sided Limit :**
	Suppose $f$ is sufficiently defined for all $x$ near $a$ with $x < a$. If $f(x)$ is arbitrarily close to $L$ for all $x$ sufficiently close to $a$ with $x < a$, we write:
$$\lim_{x \to a^-}f(x) = L$$
	and say the limit of $f(x)$ as $x$ approaches $a$ from the left equals $L$.

<span style="color: red"><b>THEOREM 2.1</b></span> **Relationship Between One-Sided and Two-Sided Limits**
	Assume $f$ is defined for all $x$ near $a$ except possibly at $a$. Then $\lim_{x \to a} f(x) = L$ if any only if $\lim_{x \to a^+} f(x) = L$ and $\lim_{x \to a^-} f(x) = L$
- Put simply, the two-sided limit exists if and only if the left-sided and right-sided limits exist and are equal.

