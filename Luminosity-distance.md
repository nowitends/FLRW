# Notes on Luminosity-Distance

#### **Deceleration Parameter ($q_0$):**
The deceleration parameter, $q_0$, is a dimensionless measure that helps in determining whether the universe is expanding at an accelerating rate ($q_0 < 0$) or a decelerating rate ($q_0 > 0$). It is defined as:

$$
q_0 = -\left( \frac{\ddot{a}}{aH^2} \right)_0 = \frac{1}{2}\Omega_0 \left(1 + 3\frac{P}{\epsilon} \right)
$$

The term $1 + 3\frac{P}{\epsilon}$ arises from the Friedmann and fluid equations in cosmology, which incorporate the effects of pressure and energy density on the universe's dynamics. The factor $\frac{1}{2}$ comes directly from the Friedmann equations when they are expressed in terms of the density parameter $\Omega_0$.

This equation effectively bridges the universe's content and geometry (through $\Omega_0$, $P$, and $\epsilon$) with its expansion behavior (through $q_0$ and $\ddot{a}$), offering a comprehensive way to describe the evolution of the cosmos under general relativity.

The negative sign in the definition implies that if the universe's expansion is accelerating ($\ddot{a} > 0$), then $q_0$ will be negative.

#### Need more details? 

The first Friedmann equation for a flat universe (assuming $k=0$ for simplicity):

   $$
   H^2 = \left(\frac{\dot{a}}{a}\right)^2 = \frac{8 \pi G}{3} \epsilon
   $$

   where $G$ is the gravitational constant and $\epsilon$ is the energy density of the universe.

The second (acceleration) equation:

   $$
   \frac{\ddot{a}}{a} = -\frac{4 \pi G}{3} (\epsilon + 3P)
   $$

   where $P$ is the pressure.

By defining the critical density $\epsilon_c = \frac{3H^2}{8 \pi G}$ and using $\Omega_0 = \frac{\epsilon}{\epsilon_c}$, we can rewrite the Friedmann equation as $\Omega_0 = \frac{\epsilon}{\epsilon_c} = 1$.

Substituting this back into the acceleration equation and rearranging terms gives:

$$
\frac{\ddot{a}}{a} = -\frac{1}{2} H^2 \Omega_0 \left(1 + 3\frac{P}{\epsilon}\right)
$$

Now, applying the definition of the deceleration parameter:
- $\Omega_0$ is the current total density parameter of the universe, which includes contributions from matter, radiation, and dark energy.
- $P/\epsilon$ represents the equation of state of the universe's content, where $P$ is pressure and $\epsilon$ is energy density.



#### **Why is the Deceleration Parameter $q_0$ Defined This Way?**

This definition originates from the desire to understand the second-order behavior (i.e., acceleration or deceleration) of the scale factor $a(t)$, which describes how distances in the universe change with time.

- $\ddot{a}$ represents the second derivative of the scale factor with respect to time, indicating the universe's acceleration rate.
- $a$ is the scale factor at the current time, representing the size of the universe.
- $H = \frac{\dot{a}}{a}$ is the Hubble parameter, which measures the rate of expansion of the universe.

The negative sign ensures that a positive value of $q_0$ corresponds to a decelerating universe (as traditionally acceleration in the direction opposite to expansion is considered deceleration in cosmology), while a negative $q_0$ indicates an accelerating universe.




#### **Dark Energy and Cosmic Acceleration:**
The observation that the universe is accelerating (i.e., $q_0 < 0$) leads to the concept of dark energy, which is a form of energy with negative pressure. This can be described by the equation of state parameter, $w = \frac{P}{\epsilon}$:

- For a cosmological constant ($\Lambda$), $w = -1$.
- For quintessence (a dynamic scalar field), $w$ varies over time but is typically less than $-1/3$.


# **Luminosity-Redshift Relation Explained**

The luminosity-redshift relation is an essential concept in cosmology, used to understand the history of the universe's expansion. This relation is especially important when using objects like Type Ia supernovae as "standard candles," which have well-known intrinsic luminosities.

## **Key Concepts:**

### **Luminosity ($L$):**
This is the total amount of energy that a cosmic object, such as a star or supernova, emits per unit time. Think of it as the object's total energy output, which is independent of the distance from the observer.

### **Redshift ($z$):**
This is a measure of how much the light from a cosmic object has been stretched (redshifted) by the expansion of the universe. A higher redshift means the object is further away, and the universe has expanded more since the light was emitted.

### **Comoving Distance ($x_{em}$):**
This is the distance between two points, measured along a path defined at the current time, considering the expansion of the universe. It represents the "straight-line" distance between two points in expanding space.

### **Scale Factor ($a(t)$):**
Describes how the size of the universe changes over time. It is normalized so that today's scale factor, $a_0$, equals 1. The scale factor at the time the light was emitted compared to now is related to redshift by $1 + z = \frac{a_0}{a(t)}$.

## **Formulas and Derivations:**

### **Energy Emitted and Observed:**
The total energy emitted by the source over a time interval $\Delta t_{em}$ is:

$$
\Delta E_{em} = L \Delta t_{em}
$$

However, due to the expansion of the universe, this energy is diluted by the time it reaches us, so the observed energy is:

$$
\Delta E_{obs} = \Delta E_{em} \left( \frac{a(t_{em})}{a_0} \right)^2
$$

This decrease is because the light is redshifted (energy decreases) and because of time dilation (observed time is stretched).

### **Observed Flux ($F$):**
The flux observed by us is the energy received per unit area per unit time:

$$
F = \frac{\Delta E_{obs}}{4\pi d_L^2}
$$

Here, $d_L$ is the luminosity distance, defined as:

$$
d_L = \left( \frac{L}{4 \pi F} \right)^{1/2}
$$

### **Clarifications:**

- **Flux vs. Luminosity:** Flux is the observed luminosity per unit area. While luminosity is an intrinsic property, flux diminishes with the square of the distance as light spreads over a larger area.

- **Understanding $d_L$ and $z$ Relationship:** The luminosity distance, $d_L$, increases with redshift, $z$. In an expanding universe, distant objects appear fainter (their observed flux decreases), meaning that $d_L$ increases with $z$. This relationship is fundamental for measuring the distances to distant galaxies and understanding the universe's expansion rate.

- **Practical Implications:**
Understanding these concepts is crucial for cosmology, as they allow astronomers to measure distances across the vast universe and to infer the rate at which the universe is expanding.




# **Luminosity-Redshift Relation:**
The luminosity-redshift relation provides a way to trace the history of the universe's expansion using luminous sources, such as Type Ia supernovae. Consider a source of luminosity $L$ (energy per unit time) located at a comoving distance $x_{em}$:

- The energy emitted by the source over a time interval $\Delta t_{em}$ is $\Delta E_{em} = L \Delta t_{em}$.
- The observed energy, accounting for the expansion of the universe, is $\Delta E_{obs} = \Delta E_{em} \left( \frac{a(t_{em})}{a_0} \right)^2$.

The observed flux $F$ at the observer is then:

$$
F = \frac{\Delta E_{obs}}{4\pi a_0^2 \phi^2(x_{em}) \Delta t_{sh}} = \frac{L}{4\pi d_L^2}
$$

where $d_L$ is the luminosity distance. For redshift $z$, the apparent bolometric magnitude $m_{bol}(z)$ is defined as:

$$
m_{bol}(z) = 5 \log_{10} z + 25 + \frac{2.5}{\ln(10)}(1 - q_0)z + O(z^2)
$$

# # **Bolometric Magnitude Explained**

Bolometric magnitude is a fundamental concept in astrophysics used to express the total energy output of stars or other celestial objects across all wavelengths of light, not just visible light. This measure gives astronomers a comprehensive understanding of an object's luminosity or total energy emission.

### **What is Bolometric Magnitude?**
Bolometric magnitude ($M_{bol}$ for absolute, $m_{bol}$ for apparent) measures the total energy emitted per unit time by a celestial object. Unlike visual magnitude, which is confined to the visible spectrum, bolometric magnitude accounts for all electromagnetic radiation emitted by the object, from radio waves to gamma rays.

### **Why Use Bolometric Magnitude?**
The use of bolometric magnitude allows astronomers to compare the total energy outputs of celestial objects directly, without the complications arising from the objects' varying emissions across different spectral bands. This provides a more uniform basis for comparison, crucial for understanding the true luminosity and energy production mechanisms of these objects.

## **Formula and Calculation:**

The bolometric magnitude is defined based on the luminosity of the object. The relationship between bolometric magnitude and luminosity is logarithmic, similar to other magnitude systems. The formula is derived from the definition of luminosity and the way magnitudes are scaled:

$$
M_{bol} = -2.5 \log_{10} \left( \frac{L}{L_0} \right)
$$

where:
- $M_{bol}$ is the absolute bolometric magnitude of the object.
- $L$ is the total luminosity of the object.
- $L_0$ is the defined zero-point luminosity in the bolometric magnitude scale, which is conventionally set to the luminosity of the Sun ($3.0128 \times 10^{28}$ watts).

For apparent bolometric magnitude ($m_{bol}$), which measures how bright an object appears from Earth, the formula incorporates distance into the calculation:

$$
m_{bol} = M_{bol} + 5 \log_{10}\left( \frac{d}{10\,\text{pc}} \right)
$$

where:
- $m_{bol}$ is the apparent bolometric magnitude.
- $d$ is the distance to the object in parsecs.
- The term $5 \log_{10}\left( \frac{d}{10\,\text{pc}} \right)$ accounts for the decrease in apparent brightness with distance.

## **Significance:**

The concept of bolometric magnitude is significant in astrophysics as it provides a uniform scale to measure and compare the total energy output of various celestial bodies. This is particularly important in studies concerning the evolution, structure, and dynamics of stars and galaxies.

Understanding an object's bolometric magnitude helps astronomers deduce its energy production mechanisms and, by extension, other physical properties like mass and age. This makes bolometric magnitude an indispensable tool in the broader field of astronomical research.


# **Cosmological Distance Measures:**
In Euclidean space, the observed flux $F$ from an object of luminosity $L$ at distance $d$ is $F = \frac{L}{4\pi d^2}$ and the angular size of an object of known length $l$ is $\Delta \theta = \frac{l}{d}$. Based on these relations, cosmologists define two important distance measures in the expanding universe:

- Luminosity distance ($d_L$): This measures how bright an astronomical object appears to an observer. It is defined as:

  $$d_L = ( \frac{L}{4\pi F})^{1/2}$$

- Angular diameter distance ($d_A$): This measures the size of an astronomical object in terms of its angular size (observed from Earth):

  $$d_A = \frac{l}{\Delta\theta}$$

where $l$ is the actual size of the object and $\Delta \theta$ is its observed angular size.


**Calculate**: $d_L(z)$ and $d_A(z)$ in a dust-dominated universe. How are they related in general? Verify that the distances $d_L$ and $d_A$ coincide only to leading order in $z$ and at small $z$ revert to the Euclidean distance $d$. In contrast with $d_A$, the luminosity distance $d_L$ increases with $z$ at large redshift, as common sense would suggest. Both, however, are only formal for $z > 1$ where the notion of invariant physical distance does not exist.

**Solution**:

In a dust-dominated universe, typically considered in cosmology as a matter-dominated universe, we analyze the behavior of luminosity distance ($d_L$) and angular diameter distance ($d_A$), particularly their relation to redshift ($z$).

#### Luminosity Distance ($d_L$):

The luminosity distance is related to observed flux ($F$) and intrinsic luminosity ($L$) of a cosmic object:

$$
d_L = \left( \frac{L}{4 \pi F} \right)^{1/2}
$$

In a matter-dominated universe, $d_L$ as a function of redshift is:

$$
d_L(z) = (1 + z) \int_0^z \frac{dz'}{H(z')}
$$

Assuming a flat universe and $\Omega_m = 1$, and considering $H(z) = H_0 (1 + z)^{3/2}$ for a matter-dominated cosmos, this can be integrated to find the relationship between $d_L$ and $z$.


The luminosity distance $d_L(z)$ can then be determined by integrating the expression:

$$
d_L(z) = (1 + z) \int_0^z \frac{dz'}{H_0 (1 + z')^{3/2}}
$$

Solving the integral, we get:

$$
d_L(z) = (1 + z) \left[ -\frac{2}{H_0 (1 + z')^{1/2}} \right]_0^z
$$

Evaluating the limits of the integral from 0 to $z$, we find:

$$
d_L(z) = (1 + z) \left( \frac{2}{H_0} \left[1 - \frac{1}{\sqrt{1 + z}} \right] \right)
$$

This provides us with the relationship between the luminosity distance $d_L$ and the redshift $z$ in a matter-dominated universe with $\Omega_m = 1$:

$$
d_L(z) = \frac{2c}{H_0} \left(1 + z - \sqrt{1 + z} \right)
$$

Here, $c$ is the speed of light, which has been reintroduced for dimensional consistency (since $H_0$ has dimensions of inverse time, and we need to convert it to distance).

#### Angular Diameter Distance ($d_A$):

The angular diameter distance, which relates an object's physical size to its observed angular size, is:

$$
d_A = \frac{l}{\Delta \theta}
$$

In cosmological terms, it's related to luminosity distance by:

$$
d_A = \frac{d_L}{(1 + z)^2}
$$

#### Relationship and Verification:

In the regime of small $z$, both $d_L$ and $d_A$ should approximate to Euclidean distance, i.e.,

$$
d_L(z) \approx d_A(z) \approx \frac{c}{H_0}z
$$

which aligns with our expectations in a locally flat space-time for low redshifts where $c$ is the speed of light and $H_0$ is the Hubble constant.

As redshift increases:

- $d_L(z)$ increases with $z$ due to the $(1+z)$ term representing the universe's expansion.
- $d_A(z)$ grows slower than $d_L(z)$ due to the factor $(1 + z)^{-2}$, making distant objects appear smaller in angular size.

Thus, for small $z$, $d_L \approx d_A \approx cz/H_0$ holds true, reflecting that at close distances (low $z$), the universe can be approximated as Euclidean. However, at high $z$, $d_L$ and $d_A$ diverge due to the effects of cosmic expansion, with $d_L \gg d_A$.

It's important to note that both $d_L$ and $d_A$ become purely formal concepts beyond $z > 1$ because the standard notion of invariant physical distance breaks down in the context of the expanding universe.

