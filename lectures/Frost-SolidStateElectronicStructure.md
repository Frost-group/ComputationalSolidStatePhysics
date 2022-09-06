![](img/2021-10-Frost-SolidStateElectronicStructure0.png)

![](img/2021-10-Frost-SolidStateElectronicStructure1.png)

![](img/2021-10-Frost-SolidStateElectronicStructure2.png)

![](img/2021-10-Frost-SolidStateElectronicStructure3.png)

![](img/2021-10-Frost-SolidStateElectronicStructure4.png)

# Solid state electronic structure & dynamics

# Jarvist Moore Frost.

![](img/2021-10-Frost-SolidStateElectronicStructure5.jpg)

Styles \+ Sizes: \(by Golden Ratio\)

36 for large headline\, Montserrat

22 for big text / small headlines\, Questrial \(Futura like\)

14 for small text\, Questrial

9 \(8\.5\) for smaller text\, Questrial

36 Montserrat \- SemiBold

22 Questrial big text  // 22 Montserrat \- SemiBold \(small headings\)

__14 for small text\, Questrial__

__9 \(8\.5\) for smaller text\, Questrial__

# Solid state dynamics

# Vibrations, phonons & all that

_Hybrid Halide Perovskites \(ABX_  _3_  _\)_

![](img/2021-10-Frost-SolidStateElectronicStructure6.png)

_A  \- Molecular Cation_

_\- '1\+' charge _

_B  \- \{Pb\, Sn\} _

_\- '2\+' charge_

_X_  _3_  _ \- Halide \{I\, Br\, Cl\*\}_

_		\- '1\-' charge_

_Weber\, Dieter\. "CH3NH3PbX3\, ein Pb \(II\)\-System mit kubischer Perowskitstruktur/CH3NH3PbX3\, a Pb \(II\)\-System with Cubic Perovskite Structure\." _

_Zeitschrift für Naturforschung B_  _ 33\.12 \(_  _1978_  _\): 1443\-1445\._

# Molecular Dynamics

__Incredibly Soft crystal__ ; large distortions of octahedra

__MA ion yaw__

__\.\.\.and roll…__

__\.\.\.CH3 clicks__

__so does NH3__

![](img/2021-10-Frost-SolidStateElectronicStructure7.png)

![](img/2021-10-Frost-SolidStateElectronicStructure8.jpg)

__\[__  __2x2x2__  __ Pseudo cubic relaxed supercell\, lattice parameters held constant during MD \(NVT simulation\)\. __  __PBESol__  __ Functional at the __  __Gamma point__  __\. __  __dt = 0\.5 fs__  __\, __  __T = 300 K __  __\]__

_Lattice Dynamics \(Phonons\)_

![](img/2021-10-Frost-SolidStateElectronicStructure9.png)

![](img/2021-10-Frost-SolidStateElectronicStructure10.jpg)

![](img/2021-10-Frost-SolidStateElectronicStructure11.png)

MAPI Low\-frequency dispersion

\(PCCP\, AMA Leguy et al\.\, 2016\)

![](img/2021-10-Frost-SolidStateElectronicStructure12.png)

# Lattice dynamics

Consider just harmonic \(quadratic\) contributions to the potential energy surface

Fill in a 'dynamic matrix' with these force\-constants

Diagonalise it\!

⇒ 'normal modes' \(eigenmodes\) which are a basis for small oscillations

![](img/2021-10-Frost-SolidStateElectronicStructure13.png)

__Why does this work?__

__Taylor expansion__

__Material is relaxed = first derivative = 0__

__We don't care about total energy__

__Dynamics start with the 2nd order contribution__

# Phonons (quantum vibrations)

* Vibrations are quantised \(ħω units of energy\)
  * Essential to understand the heat capacity of materials
  * Bose\-Einstein distribution
* Acoustic branch present in all materials \(3 in 3D\)
  * Responsible for the transmission of sound\, and also bulk modulus of a material
  * Also present in the continuum \(block of rubber\)
* If multiple atoms in unit cell \(i\.e\. there's a crystallographic basis\)\, differences in mass or force\-constants \(i\.e\. almost always\) will lead to additional bands\.
  * These always have a finite energy
  * Set up different atoms oscillating against one another
  * If these atoms have different effective charges\, this will couple dielectrically into E&M ⇒ infrared active modes
    * ? Why is it only at the Gamma point that optical phonons absorb light?

# Exploring vibrational band structure...

Online visualiser & band structure explorer

_[http://henriquemiranda\.github\.io/phononwebsite/phonon\.html](http://henriquemiranda.github.io/phononwebsite/phonon.html)_

Select a material

Look at the band structure

Click on a branch \+ energy to visualise it

Consider uploading your own 'band\.yaml' you find somewhere\, such as at:

_[https://github\.com/WMD\-group/Phonons](https://github.com/WMD-group/Phonons)_

# Solid state dynamics - redux

# Vibrations, phonons & all that

# Solid state electronic structure

Intended learning outcomes:

How does the periodicity of material give rise to an electronic band structure?

In real materials\, what extra complexity is there?

How can we extract value and interpretation from a band structure calculation?

How does one got from a band structure to a phenomenological object\, such as mobility\.

# Band structures, by tight binding

![](img/2021-10-Frost-SolidStateElectronicStructure14.jpg)

# Effective mass approximation I

Text link in case the previous embedding does not work:

_[https://youtu\.be/XtvaDn9y1L4](https://youtu.be/XtvaDn9y1L4)_

# Notes (actually the previous take…)

![](img/2021-10-Frost-SolidStateElectronicStructure15.png)

![](img/2021-10-Frost-SolidStateElectronicStructure16.png)

# Solid state electronic structure

# Band structures, for 'real' materials

![](img/2021-10-Frost-SolidStateElectronicStructure17.png)

Nicely written\! Only 80 \(book\) pages long\.

_[https://drive\.google\.com/file/d/0B3IVS9y2g3bAc1VGdXN6SW03aDQ/view?usp=sharing](https://drive.google.com/file/d/0B3IVS9y2g3bAc1VGdXN6SW03aDQ/view?usp=sharing)_

Taylor and Francis\, 1963\.

![](img/2021-10-Frost-SolidStateElectronicStructure18.png)

# Band structures

Each line is an electron \(or pair of electrons\) in  __every__  unit cell

Every point on that diagram is an electron\, delocalised over the entirely crystal\.

But what are the funny letters on the bottom?

How did a 3D electronic structure get reduced down to a few lines?

F\. Brivio et al\. Phys\. Rev\. B 89\, 155204 – Published 21 April 2014

\(Methylammonium lead iodide perovskite\.\)

F\. Brivio et al\. Phys\. Rev\. B 89\, 155204 – Published 21 April 2014

\(Methylammonium lead iodide perovskite\.\)

![](img/2021-10-Frost-SolidStateElectronicStructure19.png)

![](img/2021-10-Frost-SolidStateElectronicStructure20.png)

![](img/2021-10-Frost-SolidStateElectronicStructure21.png)

![](img/2021-10-Frost-SolidStateElectronicStructure22.png)

![](img/2021-10-Frost-SolidStateElectronicStructure23.png)

![](img/2021-10-Frost-SolidStateElectronicStructure24.jpg)

F\. Brivio et al\. Phys\. Rev\. B 89\, 155204 – Published 21 April 2014

\(Methylammonium lead iodide perovskite\.\)

See K\-path\,  <span style="color:#505050"> __Band structure diagram paths based on crystallography\, Y\. Hinuma et al\. __ </span>  _[https://doi\.org/10\.1016/j\.commatsci\.2016\.10\.015](https://doi.org/10.1016/j.commatsci.2016.10.015)_

![](img/2021-10-Frost-SolidStateElectronicStructure25.png)

![](img/2021-10-Frost-SolidStateElectronicStructure26.png)

![](img/2021-10-Frost-SolidStateElectronicStructure27.png)

# Solid state electronic structure

# Density Functional Theory & all that

Cost

DFT 			O\(N^3\)

Hybrid\-DFT		O\(N^4\)

QSGW		O\(N^4\) \+\+

CCSD		O\(N^6\)

Full\-CI		O\(N\!\)

Restaurants

VASP\, Gaussian\, xtb\, ABINIT\, Questaal\, Turbomole\, FHI\-AIMS\, DFTB\+\, DFTK\, GAMESS\(UK\)\.\.\.

_[https://en\.wikipedia\.org/wiki/List\_of\_quantum\_chemistry\_and\_solid\-state\_physics\_software](https://en.wikipedia.org/wiki/List_of_quantum_chemistry_and_solid-state_physics_software)_

Menu

<span style="color:#274E13">😊 Bulk modulus</span>

<span style="color:#274E13">😊 </span>  <span style="color:#274E13">Refined lattice size</span>

<span style="color:#274E13">😊 Bulk modulus</span>

<span style="color:#274E13">😊 </span>  <span style="color:#274E13">Lattice dynamics \(phonons\)</span>

<span style="color:#274E13">😊 </span>  <span style="color:#274E13">Molecular dynamics</span>

<span style="color:#274E13">😊 Static contribution to dielectric constant</span>

<span style="color:#B45F06">[😐](https://emojipedia.org/neutral-face/)</span>  <span style="color:#B45F06"> Band gap</span>

<span style="color:#B45F06">[😐](https://emojipedia.org/neutral-face/)</span>  <span style="color:#B45F06"> Band structure</span>

<span style="color:#B45F06">[😐](https://emojipedia.org/neutral-face/)</span>  <span style="color:#B45F06"> Effective mass</span>

<span style="color:#990000">[😑](https://emojipedia.org/expressionless-face/)</span>  <span style="color:#990000"> Optical properties</span>

<span style="color:#990000">[😑](https://emojipedia.org/expressionless-face/)</span>  <span style="color:#990000"> Optical contrib to dielectric</span>

<span style="color:#990000">[😑](https://emojipedia.org/expressionless-face/)</span>  <span style="color:#990000"> Magnetism</span>

# The time independent Schrodinger equation (TISE)

![](img/2021-10-Frost-SolidStateElectronicStructure28.png)

In this equation is all of chemistry & solid\-state physics\*\.

_\* \(The problem is that we can't solve it exactly\.\)_

# Why is solving the TISE hard?

Electron correlation\.

![](img/2021-10-Frost-SolidStateElectronicStructure29.png)

1 electron ⇒ Easy\!

Electron correlation\.

![](img/2021-10-Frost-SolidStateElectronicStructure30.png)

2 electrons ⇒ Hard

Electron correlation\.

![](img/2021-10-Frost-SolidStateElectronicStructure31.png)

![](img/2021-10-Frost-SolidStateElectronicStructure32.png)

![](img/2021-10-Frost-SolidStateElectronicStructure33.png)

![](img/2021-10-Frost-SolidStateElectronicStructure34.png)

![](img/2021-10-Frost-SolidStateElectronicStructure35.png)

![](img/2021-10-Frost-SolidStateElectronicStructure36.png)

Many electrons ⇒ Impossible\(\*\)\.

_\* \(Actually\, we can do it\, but it takes O\(N\!\) time\.\)_

# To learn about electronic structure...

* Nicely written and browsable book
* Pretty complete in covering the field
* Each chapter a few pages description\, then developed with examples
  * \(So you can flick through\)

![](img/2021-10-Frost-SolidStateElectronicStructure37.png)

# Landau's Fermi liquid theory

Small excitations of strongly\-interacting Fermi\-sea\, behave as quasi\-particles\.

The larger the excitation\, the shorter the particle lifetime\, and the worse this approximation is\.

⇒ Effective mass approximation

⇒ Calculating low\-lying optical properties is more reliable than higher ones\.

![](img/2021-10-Frost-SolidStateElectronicStructure38.png)

![](img/2021-10-Frost-SolidStateElectronicStructure39.png)

![](img/2021-10-Frost-SolidStateElectronicStructure40.png)

![](img/2021-10-Frost-SolidStateElectronicStructure41.png)

![](img/2021-10-Frost-SolidStateElectronicStructure42.png)

![](img/2021-10-Frost-SolidStateElectronicStructure43.png)

![](img/2021-10-Frost-SolidStateElectronicStructure44.png)

![](img/2021-10-Frost-SolidStateElectronicStructure45.png)

![](img/2021-10-Frost-SolidStateElectronicStructure46.png)

![](img/2021-10-Frost-SolidStateElectronicStructure47.png)

![](img/2021-10-Frost-SolidStateElectronicStructure48.png)

![](img/2021-10-Frost-SolidStateElectronicStructure49.png)

![](img/2021-10-Frost-SolidStateElectronicStructure50.png)

![](img/2021-10-Frost-SolidStateElectronicStructure51.png)

![](img/2021-10-Frost-SolidStateElectronicStructure52.png)

![](img/2021-10-Frost-SolidStateElectronicStructure53.png)

![](img/2021-10-Frost-SolidStateElectronicStructure54.png)

![](img/2021-10-Frost-SolidStateElectronicStructure55.png)

![](img/2021-10-Frost-SolidStateElectronicStructure56.png)

![](img/2021-10-Frost-SolidStateElectronicStructure57.png)

![](img/2021-10-Frost-SolidStateElectronicStructure58.png)

![](img/2021-10-Frost-SolidStateElectronicStructure59.png)

![](img/2021-10-Frost-SolidStateElectronicStructure60.png)

![](img/2021-10-Frost-SolidStateElectronicStructure61.png)

![](img/2021-10-Frost-SolidStateElectronicStructure62.png)

![](img/2021-10-Frost-SolidStateElectronicStructure63.png)

![](img/2021-10-Frost-SolidStateElectronicStructure64.png)

![](img/2021-10-Frost-SolidStateElectronicStructure65.png)

![](img/2021-10-Frost-SolidStateElectronicStructure66.png)

![](img/2021-10-Frost-SolidStateElectronicStructure67.png)

![](img/2021-10-Frost-SolidStateElectronicStructure68.png)

![](img/2021-10-Frost-SolidStateElectronicStructure69.png)

![](img/2021-10-Frost-SolidStateElectronicStructure70.png)

![](img/2021-10-Frost-SolidStateElectronicStructure71.png)

![](img/2021-10-Frost-SolidStateElectronicStructure72.png)

![](img/2021-10-Frost-SolidStateElectronicStructure73.png)

![](img/2021-10-Frost-SolidStateElectronicStructure74.png)

![](img/2021-10-Frost-SolidStateElectronicStructure75.png)

![](img/2021-10-Frost-SolidStateElectronicStructure76.png)

![](img/2021-10-Frost-SolidStateElectronicStructure77.png)

![](img/2021-10-Frost-SolidStateElectronicStructure78.png)

![](img/2021-10-Frost-SolidStateElectronicStructure79.png)

![](img/2021-10-Frost-SolidStateElectronicStructure80.png)

![](img/2021-10-Frost-SolidStateElectronicStructure81.png)

![](img/2021-10-Frost-SolidStateElectronicStructure82.png)

![](img/2021-10-Frost-SolidStateElectronicStructure83.png)

![](img/2021-10-Frost-SolidStateElectronicStructure84.png)

![](img/2021-10-Frost-SolidStateElectronicStructure85.png)

![](img/2021-10-Frost-SolidStateElectronicStructure86.png)

![](img/2021-10-Frost-SolidStateElectronicStructure87.png)

![](img/2021-10-Frost-SolidStateElectronicStructure88.png)

![](img/2021-10-Frost-SolidStateElectronicStructure89.png)

![](img/2021-10-Frost-SolidStateElectronicStructure90.png)

![](img/2021-10-Frost-SolidStateElectronicStructure91.png)

![](img/2021-10-Frost-SolidStateElectronicStructure92.png)

![](img/2021-10-Frost-SolidStateElectronicStructure93.png)

![](img/2021-10-Frost-SolidStateElectronicStructure94.png)

![](img/2021-10-Frost-SolidStateElectronicStructure95.png)

![](img/2021-10-Frost-SolidStateElectronicStructure96.png)

![](img/2021-10-Frost-SolidStateElectronicStructure97.png)

![](img/2021-10-Frost-SolidStateElectronicStructure98.png)

# Quasi-particles!

Effective \(low energy\) theory

Complicated strongly\-interacting quantum bits\, can be considered as renormalising the mass and interaction strength of the bare particle\.

![](img/2021-10-Frost-SolidStateElectronicStructure99.png)

\(A Guide to Feynman Diagrams in the Many\-body Problem\,  __R\.D\. Mattuck__ \)

# Solid state electron dynamics

# Tight binding effective mass

![](img/2021-10-Frost-SolidStateElectronicStructure100.jpg)

# Effective mass approximation II

Text link in case the previous embedding does not work:

_[https://youtu\.be/NlAKF\_xhimk](https://youtu.be/NlAKF_xhimk)_

![](img/2021-10-Frost-SolidStateElectronicStructure101.png)

![](img/2021-10-Frost-SolidStateElectronicStructure102.png)

# Solid state electron dynamics

# Band transport

# Drude model (1900):

![](img/2021-10-Frost-SolidStateElectronicStructure103.png)

![](img/2021-10-Frost-SolidStateElectronicStructure104.png)

\(Simon\, The Oxford solid state basics\)

# Sommerfield model (1927):

Why this actually works\.\.\.

![](img/2021-10-Frost-SolidStateElectronicStructure105.png)

![](img/2021-10-Frost-SolidStateElectronicStructure106.png)

![](img/2021-10-Frost-SolidStateElectronicStructure107.png)

\(Ziman\, Principles of the theory of solids\, 2nd edition\)

# DC conductivity

![](img/2021-10-Frost-SolidStateElectronicStructure108.png)

![](img/2021-10-Frost-SolidStateElectronicStructure109.png)

\(Simon\, The Oxford solid state basics\)

![](img/2021-10-Frost-SolidStateElectronicStructure110.png)

# 'Ab-initio' transport calculation

![](img/2021-10-Frost-SolidStateElectronicStructure111.png)

Phonon band structure

![](img/2021-10-Frost-SolidStateElectronicStructure112.png)

F\. Brivio et al\. Phys\. Rev\. B 89\, 155204 – Published 21 April 2014

Typically:

Born approximation \(Fermi's golden rule\)

Integrate across a double Brillouin Zone \(d^6\)

Need some kind of  __empirical scattering rate __ \(all of the complicated Fermi\-sea interactions\)

⇒ numerical Boltzmann transport equation solver \(assumes independent scattering events\)

# AC conductivity

![](img/2021-10-Frost-SolidStateElectronicStructure113.png)

![](img/2021-10-Frost-SolidStateElectronicStructure114.png)

![](img/2021-10-Frost-SolidStateElectronicStructure115.png)

![](img/2021-10-Frost-SolidStateElectronicStructure116.png)

![](img/2021-10-Frost-SolidStateElectronicStructure117.png)

![](img/2021-10-Frost-SolidStateElectronicStructure118.png)

![](img/2021-10-Frost-SolidStateElectronicStructure119.png)

![](img/2021-10-Frost-SolidStateElectronicStructure120.png)

_Approximate the complex dielectric function\,_

![](img/2021-10-Frost-SolidStateElectronicStructure121.png)

![](img/2021-10-Frost-SolidStateElectronicStructure122.png)

\(Maths\, Aschroft & Mermin; figure\, Wikipedia\)

# Band structures ⇐ ⇒ Tight binding

![](img/2021-10-Frost-SolidStateElectronicStructure123.png)

![](img/2021-10-Frost-SolidStateElectronicStructure124.png)

![](img/2021-10-Frost-SolidStateElectronicStructure125.png)

![](img/2021-10-Frost-SolidStateElectronicStructure126.png)

![](img/2021-10-Frost-SolidStateElectronicStructure127.png)

![](img/2021-10-Frost-SolidStateElectronicStructure128.png)

![](img/2021-10-Frost-SolidStateElectronicStructure129.png)

![](img/2021-10-Frost-SolidStateElectronicStructure130.png)

# Active learning component...

Let's go and get some band structures for these semiconductors\, infer some effective masses\, and calculate some mobilities\!

_[https://docs\.google\.com/document/d/1BcGytjJOZJzub\_NBA7JusYglikEhKEN\-AakUng4rDJ8/edit?usp=sharing](https://docs.google.com/document/d/1BcGytjJOZJzub_NBA7JusYglikEhKEN-AakUng4rDJ8/edit?usp=sharing)_

