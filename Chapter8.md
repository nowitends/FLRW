# Chapter Summary: Quantum Cosmological Perturbations

## Summary and Importance

- **Inflationary Universe**: During inflation, the universe expands exponentially, causing perturbations to exit the horizon and freeze their amplitudes.
- **Quantum Fluctuations**: Initial quantum fluctuations are Gaussian and evolve into adiabatic perturbations with a nearly flat spectrum.
- **Action for Scalar Field**:
  - Action: $S = \int p(X, \varphi) \sqrt{-g} \, d^4x $
  - Energy-Momentum Tensor: $T^\alpha_\beta = (\epsilon + p) u^\alpha u_\beta - p \delta^\alpha_\beta $
- **Background Evolution**:
  - Scale Factor: $a(\eta) $
  - Homogeneous Field: $\varphi_0(\eta) $
  - Friedmann Equation: $H^2 = \frac{8\pi}{3} a^2 \epsilon $
  - Energy Conservation: $\epsilon' = -3H(\epsilon + p) $
- **Perturbations**:
  - Metric in Longitudinal Gauge: $ds^2 = a^2(\eta) [(1 + 2\Phi) d\eta^2 - (1 - 2\Psi) \delta_{ij} dx^i dx^j] $
  - Perturbation Equations: 
    - $\nabla^2 \Phi - 3H(\Phi' + H\Phi) = 4\pi a^2 (\epsilon + p) \left[\frac{1}{c_s^2} \left(\frac{\delta\varphi}{\varphi'_0}\right)' + H\frac{\delta\varphi}{\varphi'_0} - \Phi \right] $
    - $\left(\Phi' + H\Phi\right) = 4\pi a^2 (\epsilon + p) \left(\frac{\delta\varphi}{\varphi'_0}\right) $
- **New Variables for Simplified Equations**:
  - $u \equiv \frac{\Phi}{4\pi (\epsilon + p)^{1/2}} $
  - $v \equiv \sqrt{\epsilon_{,X} a} \left( \delta\varphi + \frac{\varphi'_0}{H} \Phi \right) $
  - Perturbation Equations: 
    - $c_s \nabla^2 u = z \left( \frac{v}{z} \right)' $
    - $c_s \nabla^2 v = \theta \left( \frac{u}{\theta} \right)' $
    - $z \equiv \frac{a^2 (\epsilon + p)^{1/2}}{c_s H} $
    - $\theta \equiv \frac{1}{c_s z} = \sqrt{\frac{8\pi}{3}} \frac{1}{a} \left( 1 + \frac{p}{\epsilon} \right)^{-1/2} $
- **Classical Solutions**:
  - Short-wavelength: $u \approx \frac{C}{\sqrt{c_s}} \exp \left( \pm ik \int c_s d\eta \right) $
  - Long-wavelength: $u = C_1 \theta + C_2 \theta \int_{\eta_0} \frac{d\eta}{\theta^2} $
- **Quantizing Perturbations**:
  - Action: $S = \frac{1}{2} \int \left( v'^2 + c_s^2 v \nabla^2 v + \frac{z''}{z} v^2 \right) d\eta d^3x $
  - Canonical Variable: $v $
  - Mode Function: $v_k(\eta) $satisfies $v''_k + \left( c_s^2 k^2 - \frac{z''}{z} \right) v_k = 0 $
- **Power Spectrum**:
  - Power Spectrum: $\delta^2_\Phi(k, \eta) = 4 (\epsilon + p) |u_k(\eta)|^2 k^3 $
  - Short-wavelength: $u_k(\eta) \approx \frac{-i}{\sqrt{c_s k^3}} \exp \left( ik \int c_s d\eta \right) $
  - Long-wavelength: $u_k(\eta) \approx A_k \frac{(1 - \frac{H}{a} \int a dt)}{( \epsilon + p )^{1/2}} $
- **Spectral Index**:
  - Spectral Index $n_s $: Slightly less than 1, indicating a red-tilted spectrum ($n_s - 1 \approx -3 \left( 1 + \frac{p}{\epsilon} \right) - \frac{1}{H} \left( \ln \left( 1 + \frac{p}{\epsilon} \right) \right)^\cdot - \frac{\left( \ln c_s \right)^\cdot}{H} $)
  - Typical values of $n_s $range between 0.92 and 0.97.

### Importance and Meaning

- **Foundation of Cosmological Perturbations**: Understanding the quantum origins of cosmological perturbations is crucial for explaining the large-scale structure of the universe, including galaxy formation and the cosmic microwave background (CMB) anisotropies.
- **Inflationary Predictions**: The chapter confirms the inflationary model's predictions, such as the nearly flat power spectrum and the Gaussian nature of primordial perturbations, supporting the inflationary paradigm as the leading theory of the early universe.
- **Quantum to Classical Transition**: The transition from quantum fluctuations to classical perturbations explains how initial quantum randomness leads to the structured universe observed today. This is pivotal for bridging quantum mechanics and cosmology.
- **Spectral Tilt and Observations**: The prediction of a slight red tilt in the power spectrum ($n_s < 1 $) is consistent with observational data from the CMB, providing strong evidence for inflation. The specific value of $n_s $also constrains different inflationary models.
- **Role of Scalar Fields**: Scalar fields play a central role in describing the dynamics of inflation and perturbations, highlighting their importance in theoretical cosmology and potential connections to particle physics.
- **Quantization Approach**: The detailed quantization process and derivation of the action for perturbations showcase the rigorous mathematical framework required to analyze the early universe, emphasizing the interplay between general relativity and quantum field theory.

# More details

## Introduction

This chapter delves into the development of a consistent quantum theory of cosmological perturbations within an inflationary universe. Inflation stretches quantum fluctuations to macroscopic scales, freezing their amplitudes and leading to the observed nearly flat spectrum of primordial inhomogeneities.

## Quantum Cosmological Perturbations

### Action and Energy-Momentum Tensor

The action for a scalar field condensate in a flat universe is given by:

$$S = \int p(X, \varphi) \sqrt{-g} \, d^4x,
$$

where \( X \equiv \frac{1}{2} g^{\alpha \beta} \varphi_{,\alpha} \varphi_{,\beta} \). Varying this action with respect to the metric provides the energy-momentum tensor in the form of an ideal fluid:

$$T^\alpha_\beta = (\epsilon + p) u^\alpha u_\beta - p \delta^\alpha_\beta,
$$

where \( u^\nu \equiv \frac{\varphi_{,\nu}}{\sqrt{2X}} \) and the energy density \( \epsilon \) is:

$$\epsilon \equiv 2X p_{,X} - p.
$$

### Background and Perturbations

A flat, homogeneous universe is described by the scale factor \( a(\eta) \) and the homogeneous field \( \varphi_0(\eta) \), satisfying:

$$H^2 = \frac{8\pi}{3} a^2 \epsilon,
$$

and

$$\epsilon' = \epsilon_{,X} X'_0 + \epsilon_{,\varphi} \varphi'_0 = -3H(\epsilon + p),
$$

where \( X_0 = \frac{\varphi'^2_0}{2a^2} \).

### Gauge-Invariant Perturbations

The metric in the longitudinal gauge is:

$$ds^2 = a^2(\eta) \left[ (1 + 2\Phi) d\eta^2 - (1 - 2\Psi) \delta_{ij} dx^i dx^j \right].
$$

For a canonical scalar field, the "speed of sound" \( c_s \) is always equal to the speed of light (\( c_s = 1 \)). The perturbation equations in gauge-invariant variables \( \Phi \) and \( \Psi \) are:

$$\nabla^2 \Phi - 3H \left( \Phi' + H\Phi \right) = 4\pi a^2 (\epsilon + p) \left[ \frac{1}{c_s^2} \left( \frac{\delta\varphi}{\varphi'_0} \right)' + H\frac{\delta\varphi}{\varphi'_0} - \Phi \right],
$$

$$\left( \Phi' + H\Phi \right) = 4\pi a^2 (\epsilon + p) \left( \frac{\delta\varphi}{\varphi'_0} \right).
$$

### New Variables and Simplified Equations

Introducing new variables \( u \) and \( v \):

$$u \equiv \frac{\Phi}{4\pi (\epsilon + p)^{1/2}}, \quad v \equiv \sqrt{\epsilon_{,X} a} \left( \delta\varphi + \frac{\varphi'_0}{H} \Phi \right),
$$

the perturbation equations become:

$$c_s \nabla^2 u = z \left( \frac{v}{z} \right)', \quad c_s \nabla^2 v = \theta \left( \frac{u}{\theta} \right)',
$$

where

$$z \equiv \frac{a^2 (\epsilon + p)^{1/2}}{c_s H}, \quad \theta \equiv \frac{1}{c_s z} = \sqrt{\frac{8\pi}{3}} \frac{1}{a} \left( 1 + \frac{p}{\epsilon} \right)^{-1/2}.
$$

### Classical Solutions

For short-wavelength perturbations (\( c_s^2 k^2 \gg \left| \theta'' / \theta \right| \)), the WKB approximation gives:

$$
u \approx \frac{C}{\sqrt{c_s}} \exp \left( \pm ik \int c_s d\eta \right).
$$

In the long-wavelength limit (\( c_s^2 k^2 \ll \left| \theta'' / \theta \right| \)):

$$
u = C_1 \theta + C_2 \theta \int_{\eta_0} \frac{d\eta}{\theta^2} + O((k\eta)^2).
$$

### Quantizing Perturbations

The action for cosmological perturbations, inferred from the equations of motion, is:

$$
S = \frac{1}{2} \int \left( v'^2 + c_s^2 v \nabla^2 v + \frac{z''}{z} v^2 \right) d\eta d^3x.
$$

The canonical quantization variable $v $satisfies:

$$
v'' - c_s^2 \nabla^2 v - \frac{z''}{z} v = 0.
$$

Quantization leads to:

$$
\hat{v}(\eta, x) = \frac{1}{\sqrt{2}} \int \left( v_k(\eta) e^{ikx} \hat{a}_k + v_k^*(\eta) e^{-ikx} \hat{a}_k^\dagger \right) \frac{d^3k}{(2\pi)^{3/2}},
$$

where the mode functions $v_k(\eta) $satisfy:

$$
v''_k + \left( c_s^2 k^2 - \frac{z''}{z} \right) v_k = 0,
$$

with the normalization condition:

$$v'_k v_k^{*} - v_k v_k^{*}' = 2i.
$$

### Spectrum of Perturbations

The power spectrum of the gravitational potential is:

$$
\delta^2_\Phi(k, \eta) = 4 (\epsilon + p) |u_k(\eta)|^2 k^3.
$$

For short-wavelength perturbations:

$$
u_k(\eta) \approx \frac{-i}{\sqrt{c_s k^3}} \exp \left( ik \int c_s d\eta \right).
$$

For long-wavelength perturbations during inflation:

$$
u_k(\eta) \approx A_k \frac{(1 - \frac{H}{a} \int a dt)}{( \epsilon + p )^{1/2}}.
$$

Matching conditions at horizon crossing yield a nearly scale-independent power spectrum:

$$
\delta^2_\Phi(k) \approx \frac{64}{81} \frac{\epsilon}{c_s (1 + p/\epsilon)} \bigg|_{c_s k \approx Ha}.
$$

### Spectral Tilt

The spectral index \( n_s \) is slightly less than 1, indicating a red-tilted spectrum:

$$
n_s - 1 \approx -3 \left( 1 + \frac{p}{\epsilon} \right) - \frac{1}{H} \left( \ln \left( 1 + \frac{p}{\epsilon} \right) \right)^\cdot - \frac{\left( \ln c_s \right)^\cdot}{H}.
$$

Typical values of \( n_s \) range between 0.92 and 0.97 depending on the specific inflationary model.

## Conclusion

Quantum fluctuations generated during inflation lead to the formation of macroscopic structures in the universe. The detailed treatment of quantum perturbations provides insight into the spectrum and nature of these primordial inhomogeneities, reinforcing the robustness of inflationary predictions.
