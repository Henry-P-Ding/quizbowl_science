---
tags:
  - state_function
categories:
  - science
  - chemistry
  - physics
  - thermodynamics
answers:
  - Gibbs free energy
---
### Categories
[[chemistry]], [[physics]], [[thermodynamics]]

### Answer Lines
[[Gibbs free energy]]
## Notes
The **differential form** of Gibbs free energy is:
$$
\diff G = V\diff P - S\diff T
$$
- Proof:
	1. Note that $dH = dU + d(PV)$ by the definition of [[enthalpy]].
	2. The [[First Law of Thermodynamics|First Law]] states that: $$\diff U = T\diff S - P\diff V$$
	3. Then: $$\diff H = T\diff S + V\diff P$$
	4. Note that $$\diff G = \diff H - \diff(TS)$$
	5. Then: $$\begin{align*}
		\diff G &= T\diff S + V\diff P - T\diff S - S\diff T \\
		\diff G &= V\diff P - S\diff T
	\end{align*}
	$$

The [[natural variables]] for Gibbs free energy are [[pressure]] $P$ and [[temperature]] $T$.