---
title:  "Dielectrics"
date:   2021-02-15 16:46:55 -0500
categories: projects
layout: default
---
In this post, I will be going over some basic concepts in ElectroDynamics. The objective is to build up the prior knowledge required to understand COSMO ("COnductor-like Screening MOdel") solvation models. I hope that this series of posts can be helpful to those with an engineering mindset who are getting into the world of quantum chemistry.

Dielectrics
---

Most matter is categorized as **conductors** or **insulators**. Conductors have an abundance of electrons that float freely through the material. A typical metal has one or two electrons per atom shared all across. Conversely, insulators (or **dielectrics**) have their electrons on leashes. The electrons make microscopic displacements within the atom or molecule once subjected to an electric field.

If we place a neutral atom in an electric field, our intuition will lead us to believe that the cloud of electrons would displace by a certain distance from its origin, leaving the atom polarized. A better way to illustrate this concept would be to consider the following rudimental model of an atom. It consists of a point nucleus ($$+q$$) surrounded by a uniformly charged spherical cloud ($$-q$$) of radius $$a$$. When $E$ is applied, the neucleus moves with the field to the right by a distance $$d$$. At equilibrium, the external field $$E$$ pushing the neucleus to the right exactly balances the internal field pulling it to the left created by the cloud of electrons $$E_e$$.

<br/>
<p align="center">
  <img src="/assets/images/neutral_atom_dielectric.png" />
  <legend>Fig. 1</legend>
</p>

At equilibrium, $$E = E_e$$. Now the field at a distance $$d$$ from the center of a uniformly charged sphere is:

$$ E_e = \frac{1}{4\pi\epsilon_o} \frac{qd}{a^3} $$
