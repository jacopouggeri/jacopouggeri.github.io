---
title: "Shining Light on Missing Red Giants: Red Giant Photoevaporation in the Galactic Centre" 
date: 01/05/2023
url: /msci/
tags: ["red giant","black hole","photoevaporation","galactic centre","astrophysics","stellar evolution"]
author: "Jacopo Uggeri"
supervisor: "James Owen"
description: "The project's aim was to investigate whether the lack of red giant stars at the center of the Galaxy could be explained by evaporation caused by radiation coming from the accretion disk of the central supermassive black hole." 
summary: "The project's aim was to investigate whether the lack of red giant stars at the center of the Galaxy could be explained by evaporation caused by radiation coming from the accretion disk of the central supermassive black hole. Our results provided promising evidence that photoevaporation can indeed significantly alter a red giant's evolutionary course." 
cover:
    image: "/img/msci_img.png"
    alt: "Shining Light on Missing Red Giants: Red Giant Photoevaporation in the Galactic Centre"
    relative: false

---

![](/img/msci_img.png)
Figure 2.1: Model and Theory

---

### Abstract

The observed distribution of red giant stars in the galactic centre deviates from the cusp-like arrangement predicted by theoretical and computational models. Existing explanations have thus far proven insufficient to account for this discrepancy. In this thesis, we propose a novel mechanism, wherein radiation from an accreting supermassive black hole heats the outer layers of these stars, causing them to eject mass in the form of a Parker wind. Our aim is to explore whether this photoevaporative process can offer an alternative explanation for the observed distribution of red giants in the galactic centre. We first calculate the spectrum of radiation emitted by the accretion disc and subsequently determine the ionisation fraction outside the star to find the base of the flow. With this knowledge, we apply the solutions for a steady Parker wind to find the mass loss rate. Our findings align with initial estimates and reveal that photoevaporation could have a substantial impact on the evolution of red giants near the galactic centre. We identify a specific region in our parameter space of stars that experience significant mass loss rates, which could affect their distribution over the span of 3 million years. This study presents a compelling case for further investigation of the photoevaporation hypothesis in order to ascertain its role in shaping the distribution of red giants in the galactic centre, with potential implications for the study of both the Milky Way and other galaxies.

---

### Additional Information
Exciting news! I will be working with my supervisor, Dr. James Owen, to extend this project. Currently, the stellar evolution code is very approximate and can only offer a qualitative predictions on the behaviour of the star (ie will it evaporate?). Furthemore, these predictions match pretty closely with the rough estimates of evaporation timescale obtained by the instantaneous mass loss and the star's mass. However, we would like to extend this project to include a more accurate stellar evolution code, which will allow us to make quantitative predictions on the star's evolution.

To do so, I am modifying [MESA](https://docs.mesastar.org/), a research-grade stellar evolution code, by altering the mass loss physics to include the previously calculated mass loss rates. This will allow us to get much more precise answers to questions such as: how much mass will the star lose? How will this affect its evolution? How will this affect its distribution in the galactic centre?

---

### Download

+ [Project Report](/docs/msci.pdf)
+ [Code and data](https://github.com/jacopouggeri/red_giant_photoevaporation)

### Related material

+ [YouTube Presentation](https://www.youtube.com/watch?v=DIE3EIqZb9M&t=18s)
