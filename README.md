# Quantum Espresso on Google Colaboratory (Colab) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sedaoturak/Quantum_Espresso_Colab/blob/master/Quantum_Espresso_Colab.ipynb)

<p align="center">
  <img src="https://github.com/sedaoturak/Quantum_Espresso_Colab/blob/main/pic.png" width=350/>
</p>

[**Google Colab**](https://colab.research.google.com/) is a platform which provides an online computing sources to develop and work on coding projects, or even to teach coding or specific topics like modeling-simulations of physical phenomena in the schools.
[**Quantum Espresso (QE)**](https://www.quantum-espresso.org/)[[1](https://iopscience.iop.org/article/10.1088/0953-8984/21/39/395502/meta?casa_token=g1evgUWAyAAAAAAA:PBNGb3BGEogp8Uq9leLCquTamf_lSoWY6TnAvDilAbX4iAts9OQIpkqhi6l-8f9fHpglr6hDtw)] is a widely-used open-source materials modeling software at nanoscale by performing [**density functional theory (DFT)**](https://en.wikipedia.org/wiki/Density_functional_theory). DFT is the fundamental step in multiscale materials modelling (please see the figure below, taken from [[2](https://link.springer.com/article/10.1007/s40544-018-0207-9)]). The most preferred method to use QE is installing it on a local computer together with necessary files (input, pseudopotentials) and packages/libraries like AiiDA or gnuplot, and executing the every every step by a command through the terminal.
<p align="center">
  <img src="https://github.com/sedaoturak/Quantum_Espresso_Colab/blob/main/multiscale.jpg" width=450/>
</p>
<div align="center">
  Multiscale materials modelling framework. DFT takes the very first step.
</div>


This repository includes an example notebook showing how to install and use **QE on Colab**. This might be a quite **useful go-to method** for especially **educational purposes of atomistic modeling** in the schools. It just needs the pseudopotential files to be uploaded on the Colab directory -"Files" section on the left menu. Also, it is easier to **modify the input file seamlessly** and **run multiple simulations consecutively**. To show this in an example, a loop for convergence test is shared at the end.

**Advantages of this notebook:**
- Easier input file preparation and modifications
- Easier access the information in input and output files
- Automatic, parametric simulations in a Python loop (E.g. convergence test)
- Simpler installation and usage of the Quantum Espresso package
- Direct visualization of the materials that are simulated

You're very welcome to share, use and contribute!
