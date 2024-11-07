# Solid dosage forms dissolution models

Immediate or extended release drug product are characterized by their Active Pharmaceutical Ingredient (API) dissolution profile, tested according to USP <711> or Ph. Eur. 2.9.3 monographs.

Several models have been proposed to fit the dissolution profile across time, $y(t)$:
* **Weibull Model** based on diffusion: $y(t) = p(1-e^{-zt})$

where $p$ is a *potency factor* (= dissolution plateau fraction value, set to 1 if the total quantity of API is released) and $z$ is a *kinetic dissolution factor* (higher z, faster dissolution).


* **Modified Weibull Model**: $y(t) = p(1-e^{(-zt)^k})$

which introduces an additional *scale factor* $k$, meant to better fit experimentally observed dissolution profiles.


* **Noyes-Whitney Model** expressed by the differential equation: $\frac{dy(t)}{dt} = z(p-y(t))^n (s-y(t)\frac{dose}{v})$

which considers the effect of the API concentration gradient during the dissolution through the term $(s-y(t)\frac{dose}{v})$, where $s$ is the *API solubility* in the dissolution media, $dose$ is the *API dose* in the drug dosage form and $v$ is the *volume* of dissolution media.

**OBJECTIVE**:

The objective of this project is to explore the influence of various modelling parameters on the dissolution profile and develop a tool to fit a profile based on experimental measurement of dissolution profiles. 
