[![License: MIT](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE.md)

# FEM Analysis - Helicopter's Tail

This work performed during the master course of Modeling and Design with Finite Elements, for the part about the course’s project, developed in team with ANSYS Mechanical APDL Software.
The purpose is to present a consistent finite-element formulation, developed to predict the free vibration characteristics of two different helicopters tailboom structures.
Both airframes considered for our analysis are taken from real-world widespread helicopters types; the first model regards the tail of a **Lama SA-315b** which is an old type of reticular steel structure, quite easy to design and manufacture, while the second model represents a modern semi-monocoque tail design that consists in an ensemble of an aluminium skin layer connected with other structural elements and commonly adopted in modern rotor-craft’s airframes like the one of the **Eurocopter AS-350** ecureuil.
The work has been organized in a sequence of __steps of increasing complexity and accuracy__. Initially the problem has been approached by independent investigations of the free vibrational behaviour of the two different airframes (*uncoupled tailrotor-fuselage dynamic model*). Thus, results are obtained for the naked structures only. Then, the tailboom’s models have been improved taking into account also the presence of additional sub- systems normally fixed on helicopter’s tail and the system’s natural frequencies have been recalculated. Furthermore, some theoretical hints on how to take into account the *tailrotor-fuselage dynamic coupling*, which considers also the interaction of the effects related to the the tail-rotor rotation. This last step is quite ambitious, the topic is wide and complex, however it should be considered to develop a model which is accurate enough to study the real system’s vibrational behaviour.
The last part, instead, is aimed to explore the Ansys’ Rotor-dynamic capabilities and tools which are only recently implemented in the software. A great deal of efforts have been done to understand the physical phenomena and try to implement a simple model from the rotor-dynamics point of view. However, this can be done only under important simplifying assumptions. For our purposes, this part is only limited to study the rotor’s vibrational behaviour which turns to be velocity dependent (varies with tail rotor speed).

## Report
The complete report about dynamic analisys for tailboom helicopter is aviable [here](https://github.com/frank1789/FEM-Analysis---Helicopter-s-Tail/Report/Ansys_Report.pdf)

## Authors

* **Francesco Argentieri**
    + macro code
    + shell model  
    + rotordynamics:
        + modal analisys
        + harmonic anlaysis - transient
    + report
* **Lorenzo Beatrici**
    + truss model
    + report
* **Luca Nicolodi**
    + truss model
    + report

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* ANSYS Mechanical APDL Rotordynamic Analysis Guide
* Introduction to APDL - second editon
* etc
