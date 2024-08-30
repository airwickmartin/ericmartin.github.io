---
title: "Capstone Research Project"
description: "**objective: to develop an active radiation shield for interplanetary spacecraft**"
summary: "ME 352"
weight: 3
---

*advisors: Prof. John Pfotenhauer, Assoc. Profs. Paolo Desiati & Elena D’Onghia*

*client/funding: NASA Innovative Advanced Concepts (NIAC)*

Active magnetic shielding is a unique approach to protecting astronauts from harmful space radiation during extended journeys.
By configuring superconducting electromagnetic coils around a spacecraft into a Halbach array, a strong magnetic field is generated, offering greater protection than passive material shielding.

After two challenging semesters of research, I chose this project as my senior design capstone and assembled a team of three mechanical engineering students to develop a proof-of-concept for the shield’s support structure.

{{< figure src="/p1_pic1.png" title="team poster review" width="85%" >}}

Our primary focus was on designing internal coil supports capable of withstanding complex Meganewton-scale Lorentz forces while keeping weight to a minimum. 
We also designed components like I-beams and mounting, but the intricate loading on the coils demanded the majority of our attention.

Initially, we tried using SolidWorks Topology Optimization for our designs, but we weren't confident in the software's handling of the complex loading distributions.
Our design process evolved through several iterations, starting with intuitive approaches like hexagonal and multi-bar structures. 
These early prototypes, while promising, fell short of meeting the strain and surface area requirements set by our advisors and client.

{{< figure src="/p1pic2.png" title="left: biomimetic honeycomb structure, right: intuitive truss structure" width="75%" >}}

Halfway through our senior year, we reached a turning point. We knew that such a complex project would require an innovative solution, so we reached out to department Prof. Krishnan Suresh, a topology optimization specialist.
He granted us licenses for his proprietary software and provided guidance on best FEA practices, ultimately leading to our final design.

{{< figure src="/p1gif1.gif" title="left: simulation of complex saddle loading, right: topology optimization (ParetoWorks)" width="85%" >}}

Interestingly enough, armed with new insights, we revisited our initial SolidWorks attempts. By redefining boundary conditions and utilizing symmetry we achieved design convergence, the most satisfying end to the most intricate project.

{{< figure src="/p1pic3.png" title="" width="90%" >}}

Over the two semesters, the team made notable advancements in developing the support structures. 
The final design achieved a maximum strain of 0.37% and an average strain of 0.001%, well below the superconducting cable's limit of 0.45%. 
The structure experienced a maximum stress of 40 Megapascals, comfortably within aluminum's yield strength of 275 Megapascals.
In order to achieve this success, we maintained continuous dialogue with stakeholders throughout the project lifecycle.

{{< figure src="/p1pic4.png" title="" width="90%" >}}

By clearly defining these stakeholders, we gained valuable perspective that motivated our work while ensuring our designs aligned with the aerospace industry's demands.
This human-centric process not only led to a design that exceeded our initial specifications but also demonstrated the power of iterative concept development in solving some of the world's most complex engineering problems.

**Final Reports:**

- [Project Report PDF](/proj1doc1.pdf)

