# Tutorials for PyOR (Python on Resonance)
## Everybody can simulate NMR
Author: Vineeth Thalakottoor (vineethfrancis.physics@gmail.com)

## PyOR developers
- Main contributor: Vineeth Francis THALAKOTTOOR JOSE CHACKO
- Other contributors: --- (I welcome contributors after the first release of PyOR)

## Why develop PyOR when many NMR simulation packages are available? Why reinvent the wheel?
The short answer: "The Pleasure of Finding Things Out".

## Why Python??
The answer is: it's free.

## PyOR is for?
PyOR will be helpful for beginners (with basic knowledge of NMR and Python programming) interested in programming magnetic resonance pulse sequences and relaxation mechanics.

## Features implemented in PyOR
- Spin operators (Sx, Sy, Sz, S+ and S-) for any number of particles with any spin quantum number.
- Hamiltonians: Zeeman (lab and rotating frame), B1, J coupling, Dipolar.
- Suporoperators
- Various ways to plot Matrix and expectation values.
-  Time Evolution of Density Matrix
  - Evolution in Hilbert Space
    - Unitary Propagation
    - Solve ODEs
    - Radiation Damping, Raser/Maser (single and multi-mode)
    - Relaxation Mechanisms (Redfield)
      - Phenomenological
      - Auto-correlated Random Field Fluctuation
      - Auto-correlated Dipolar Homonuclear
      - Auto-correlated Dipolar Heteronuclear
  - Evolution in Liouville Space
    - Unitary Propagation
    - Solve ODEs
    - Relaxation Mechanisms (Redfield)
      - Phenomenological
      - Auto-correlated Random Field Fluctuation
      - Auto-correlated Dipolar Homonuclear
      - Cross Correlated CSA - Dipolar Hetronuclear
      - Redfield Kite (Redkite)

## Features to implement in PyOR
- Shaped Pulses (Amplitude and Phase modulated RF pulses)
- Lindblad Master Equation
- and more
