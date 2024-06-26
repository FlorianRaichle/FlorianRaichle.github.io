---
author: Florian Raichle
type: thesis
bibliography: 'bibliography.bib'
csl: 'ieee.csl'
date: 'November 08, 2021 - May 23, 2022'
title: Simulation of adsorption on moving particles using the Eulerian-Eulerian
    lattice Boltzmann method
description: "My master thesis developing an adsorption model for the lattice Boltzmann method."
resources:
- src: Ma-FlorianRaichle.pdf
  title: Thesis
weight: 1
---

Abstract
========

To simulate adsorption in industrial applications and gain more insight
into the coupling of fluid flow and adsorption performance, adsorption
models at larger scales than just single particles are needed. In this
thesis a model of the adsorption on moving particles is applied to the
lattice Boltzmann method using an Euler-Euler approach. The adsorption
model is based on mass transfer as described by the linear driving force
model and can incorporate several mass transfer mechanisms, such as film
diffusion, surface diffusion and pore diffusion. Particles, their
adsorbate loading, and the solute are described by the advection
diffusion equation with an adsorption source term.

Using analytical solutions for a batch and fixed bed reactor the model
and its coupling with the fluid is validated. Grid studies are conducted
to show the convergence of the model. The applicability of the model to
complex flow problems is demonstrated in a static mixer with moving
particles.

Problem Statement and Approach
==============================
Adsorption is ostensibly best described using individually resolved particles.
This approach however becomes untenable when larger and more complex fluid problems need to be solved.
Therefore the goal of this thesis was the development of an adsorption model for the Euler-Euler approach where particles are treated as a continuum.
The linear driving force model was chosen because it is suitable for this approach while still being reasonably accurate and based on physical mechanisms. 

{{< a href="MA-FlorianRaichle.pdf" download="MA-FlorianRaichle" >}}
Get the pdf here
{{< /a >}}