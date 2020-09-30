Introduction
============

In this final part of the course, we will use computational tools to understand
solid-state physics. Solid-state physics is complex and messy (Murray Gell-Mann
described it as the ‘squalid-state’). In an undergraduate curriculum we are
limited to what we can understand analytically, and calculations that are
tractable by hand. Therefore we are limited to non-interacting quantum
theories, and one-dimensional ‘toy’ examples of perfect ‘crystals’. Real
materials are firmly embedded in a three dimensional world. Much important
technical behaviour (even of crystals) is dictated by very low concentrations
of disorder or dopants in the material. In molecular materials, the
microstructure (how the material packs) is of high importance for electrical
and optical properties, but extremely difficult to probe experimentally.

Everything we see and touch and hear is due to the electronic structure of
materials. Due to its large mass, the atomic nucleus (at energies we care
about!) is effectively a point charge. The much lighter electrons delocalise
quantum mechanically, and form the atomic orbitals with hybridise into covalent
bonds, and the bonds which delocalise in the solid state to provide the band
structure of a material. Therefore, to predict any and all behaviour of
a material, we simply need to solve the Schroedinger equation of motion that
governs the electron dynamics. 

Unfortunately, this calculation is totally intractable with a classical
computer! The equations have been known since the 20s, and a practical
algorithm (called ‘configuration interaction’) since the 30s. But the
computational cost scales as the factorial of the number of electrons in your
system (O(N!) in Knuth’s big-O’ notation). This is a problem. Even solving
a moderately sized system (dozens of atoms) would require a supercomputer
running until the heat death of the universe[^largestCIcalc]. A single gram of
a solid-state material contains about10^23 electrons. 

[^largestCIcalc]: The largest configuration interaction calculation I am aware
  of is this 2017 work, where they pushed NWCHEM with a new implementation to
  20 electrons in 20 orbitals. {cite}`Vogiatzis2017`

  Faced with this insurmountable computational cliff, many clever
  approximations have been developed. If you are a physicist, you describe this
  area of research as ‘electronic structure theory’, and if you’re a chemist,
  as ‘quantum chemistry’. The most successful theory is the beautiful  ‘density
  functional theory’ (DFT), made practical in the 1980s by linearisation, and
  more accurate in the 1990s by the clever kludge of ‘hybrid density functional
  theory’. 

  These approximations are eye-achingly complex and subtle. Many of these
  approximations are ‘uncontrolled’ in that it is not known ahead of time
  whether they under or overestimate the predicted quantity. None of the
  approximations are actually that good or universally applicable. You can tell
  this by the fact that there are so many different methods still in use - if
  one actually worked, we’d just that one, and stop talking about it so much!
  (Famously DFT fails even for the seemingly trivial case of disassociating
  H2+.) Most progress in applying these methods to real materials has been
  brought about by the implementation of these methods in easy to use computer
  codes, allowing other researchers to effectively use the methods as ‘black
  boxes’. 

  This is a major problem for the progress of our field. Experiment always
  needs to be backed up by theory. In solid-state materials, this theory almost
  always needs to be computational (due to complex materials). And if your
  computational theory is a black box, you’re not really adding much
  understanding, just showing that you can reproduce nature. 

  So the focus of this small part of the course is to try and teach you the
  skills to interpret what these highfalutin computational methods are
  calculating, and to try and show you how to peel back the layers to get to
  something malleable that you can work with. 

