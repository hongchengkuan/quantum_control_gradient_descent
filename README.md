# Quantum Control via Gradient Ascent
This package provides a way to use gradient ascent to optimize the transition probability.

See the matlab/demo.m and python/demo.py for usage.
## Experiments
### The gound state to the first excited state
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1/0to1_morse.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1/Ef.png" height="350" width="430">
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1/0to1rabitz.png" height="350" width="430"> [Zhu, Botina and Rabitz, 1998]

### The third excited state to the fifth excited state
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5/3to5.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5/Ef.png" height="350" width="430">
### The third excited state to the fifth excited state (the same time as in [Zhu, Botina and Rabitz, 1998]) 
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5longer/3to5.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5longer/Ef.png" height="350" width="430">
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5longer/3to5rabitz.png" height="350" width="430">[Zhu, Botina and Rabitz, 1998]

#### Enlarge the electric field in a small period of time
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/3to5longer/Ef0-31250.png" height="350" width="430">

### The fourth excited state to the fifth excited state
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/4to5/4to5.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/4to5/Ef.png" height="350" width="430">
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/4to5/4to5rabitz.png" height="350" width="430">[Zhu, Botina and Rabitz, 1998]
### The ground state to the superposition between the first and the second excited state
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1-2/0to1-2.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1-2/Ef.png" height="350" width="430">
### The ground state to the superposition between the first and the third excited state
<img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1-3/0to1-3.png" height="350" width="430"><img src="https://github.com/hongchengkuan/quantum_control_gradient_ascent/blob/master/0to1-3/Ef.png" height="350" width="430">
### Acknowledgements

Christian R. Shelton proposed to use dynamic progamming for the calculation of the gradient.

The line search and conjugate gradient ascent are based on "A COKOSNUT code for the control of the time-dependent Kohn–Sham model" by M. Sprengel, G. Ciaramella and A. Borz&#204;.

The initial Crank-Nicolson implementation of the Sch&#246;dinger equation was due to Bryan M. Wong and Akber Raza.
