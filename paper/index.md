---
# modify this according to your needs
title: Project Elara Technical Overview
short_title: Technical Overview
bibliography:
  - citations.bib
---

+++ { "part": "abstract" }
Project Elara is a nonprofit dedicated to being part of creating a future powered by plentiful space-based solar power. Scientific research is an essential component of the project and the basis of its technological work. In ensuring the full benefits of the research are realized, the project publishes all results and tools openly and works on a nonprofit basis&mdash;all work within the Project is dedicated to the public domain. This technical overview details the present research and development conducted by the Project.
+++

```{warning}
Project Elara has switched over to the open-source forge [Codeberg](https://codeberg.org/). The Project Elara repositories have been moved to [this Codeberg page](https://codeberg.org/elaraproject/), and the most recent version of the paper can be found on the [new Project Elara research website](https://research.elaraproject.org/technical-overview/). **This version of the paper is no longer maintained**.
```

# High-level overview

Project Elara ("_hope_") aims to conduct research and eventually development of advanced technologies that we envision will bring about a better future. Our priority research is in the realm of space-based energy harvesting with large-scale space-based solar power constellations. Achieving this capability, if done carefully and correctly, would provide a stable, lasting energy source orders of magnitude more powerful than any contemporary or near-future capabilities. Such a system opens the doorway to engineering and construction on a planetary, if not stellar scale, including mass interplanetary travel, powering space habitats, and even possibly the propulsion of interstellar lightsail arks. To us, these are steps that, if taken in a responsible and wise manner, can lead towards a truly peaceful and equitable future.

The development of such a system is not solely for the purpose of space-based power. Various near-term technologies would also be greatly benefitted by the successful development of this technology. To simply name a few, the benefits could include improved internet as well as greater power equity and accessibility for rural communities and developing nations, improved satellite communications, improvements in laser surgery, high-precision optics for science experiments such as gravitational wave interferometry, and improvements in inertial confinement fusion.

However, it is no doubt that such an undertaking must begin with small initial steps and will require countless contributions, potentially over multiple generations. Thus the present work of the Project is incremental and small-scale, with the hope of achieving more with time. We are focused on several key technologies that are critical to making space power constellations a possibility: high-gain ultra-long-distance microwave transmission, persistent space-ground communication, and safe wireless power transfer at high power. These are the areas of our immediate computational research.

# Technical description of research

Our first research milestone is to achieve accurate theoretical and computational modelling of long-distance power transmission. Both analytical and numerical methods are used for analyzing electromagnetic energy transport, and to investigate how high-gain, all-weather transmission may be achieved, with specific emphasis on precision optics. 

Initial research has produced a proof-of-concept model that has been used in computational electromagnetics simulations, which we detail in our [2024 end-of-year report](xref:project-yearly-report). An example of our simulations can be found in [](#fig1). These simulations use finite-element methods to obtain numerical solutions to the electromagnetic Helmholtz equation, and finite-difference methods to perform validation testing. While the model is proof-of-concept and experimental, it represents a key breakthrough and a stepping stone towards a complete, consistent, research-ready solver.


:::{figure} fig/example-simulation.png
:label: fig1
:alt: A plot of a numerical simulation of the Helmholtz equation
:align: center

An example of our computational simulations of wave propagation
:::

Prospective research consists of the refinement of this model to produce an improved model ready for producing publication-quality results. The improved model is expected to integrate more advanced models, such as atmospheric attenuation via the ITU-R P.676-13 atmospheric attenuation model [@itur676] and a hybrid GOCE6-GGM03-EGM2008 gravitational model for accurate orbital modelling (@EGM2008, @GOCE6, @GGM03). Furthermore, unlike the proof-of-concept model, the improved model will be a multiphysics model that integrates more (eventually, all) aspects of the system.

More computational simulations will allow fine-tuning the design of the concept space-based solar power constellation and in turn be used to make more accurate simulations of the system. This iterative process is expected to continue for a significant portion of time, until sufficient computational testing has yielded a highly-detailed design that can be built into functional prototypes. Ground testing and atmospheric tests are then expected to progress, with a further test-design-simulation cycle to continue adding refinements. This process is expected to continue until design finalization. 

# Distinctive features of the project

Given its ambitious aims, the Project is not meant to be a short-term project. At Project Elara, we take careful measures to safeguard the longevity of the Project. The Project is open-source: all published documentation of the Project is freely available online, and eventually, is projected to be made available, at an affordable cost, in book form. The loss of the project organization or of its team would not constitute the end of the Project. The project is deliberately designed such that it can be picked up and continued at any point from its encyclopedic handbook, as well as further books that contain fully-commented source code, design specifications, and blueprints. As mentioned, all of its books and documentation are fully dedicated to the public domain.

# Team members

Our team consists of project head and research lead Jacky Song, co-researchers Emiliano Vilchis and Nicholas Schnorbus, general advisor Charles Wang, and engineering advisor Milo Schnack, with support from Professor Peter Persans, Professor Trevor Rhone, and Professor Heidi Newberg at Rensselaer Polytechnic. We welcome anyone to join and have a Discord channel as well as informal meetings for discussions. There is no bar to entry, nor any necessary qualifications required.

# Futher information

The [project website](https://elaraproject.github.io/) and [GitHub](https://github.com/elaraproject) provide more information about the project and an opportunity for anyone interested to learn more. For official inquiries, please email us at <elaraproject@gmail.com>. We would also be glad to take meeting requests, virtual or in-person (if availability allows).
