# Reactor-Modelling Examples for Ullmann's Encyclopedia "Model Reactors and their Design Equations"

This repository contains executable Jupyter notebooks accompanying the Ullmann's Encyclopedia of Industrial Chemistry contribution:

> Jens Bremer and Robert Güttel, *Model Reactors and Their Design Equations*, Ullmann's Encyclopedia of Industrial Chemistry.  
> **Article DOI:** to be added after publication.

The notebooks provide reproducible implementations of the six worked examples presented in the article. They connect the balance equations and reactor models discussed in the manuscript with their numerical solution, visualization, and optimization in Python.

## Examples

1. **Thermal stability of a CSTR**  
   Steady-state multiplicity and thermal stability of a cooled continuous stirred-tank reactor with consecutive reactions.

2. **Non-isothermal plug-flow tubular reactor**  
   Axial concentration and temperature profiles, including adiabatic and polytropic operation and hot-spot formation.

3. **Reaction-diffusion problem at the meso-scale**  
   Numerical solution of a one-dimensional reaction-diffusion model for a gas-liquid reaction.

4. **Spatial integration and reactor-length optimization**  
   Spatial integration of a plug-flow reactor model and optimization of reactor length and operating temperature.

5. **Finite-volume simulation of steep thermal fronts**  
   Transient finite-volume simulation, grid refinement, numerical diffusion, and integration of a stiff semi-discrete reactor model.

6. **Two-dimensional reactor hot spots and parameter fitting**  
   Axisymmetric reactor simulation with axial and radial transport, followed by parameter estimation from synthetic measurement data.

## Running the notebooks

The examples require a recent Python installation and the following main packages:

```text
numpy
scipy
matplotlib
jupyter
```

Open the repository in JupyterLab or Jupyter Notebook and execute the notebooks in numerical order. Each notebook contains the model equations, parameter definitions, numerical workflow, result evaluation, and figure generation required for its example.

```bash
jupyter lab
```

Some publication figures are exported as vector PDF files and as numerical data for direct use with PGFPlots in LaTeX. A working LaTeX installation is therefore recommended for reproducing the final article-style figures.

## Data and reproducibility

The archived release of the notebooks and accompanying files is available on Zenodo:

**https://doi.org/10.5281/zenodo.21553881**

The Zenodo DOI should be used when citing the software and reproducibility package. Once the Ullmann's article has been published, its DOI should be inserted in the article reference above to provide an explicit link between the publication and this repository.

## Citation

Until the article DOI is available, please cite the accompanying software archive as:

> Bremer, J.; Güttel, R. (2026). *Examples for Model Reactors and Their Design Equations*. Zenodo. https://doi.org/10.5281/zenodo.21553881

After publication, please cite both the Ullmann's contribution and the Zenodo software archive.

## Authors

- Jens Bremer, Clausthal University of Technology
- Robert Güttel, Ulm University

