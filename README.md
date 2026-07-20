# Scaffold-Design-Simulator

A computational tool for comparing biomaterials used in tissue engineering scaffolds, built as a personal project to apply bioengineering concepts through Python.

## What it does
- Compares 8 biomaterials (PLGA, Collagen, Alginate, PCL, and more) across key scaffold properties including porosity, pore size, and degradation rate
- Calculates a custom **Scaffold-Tissue Match Score** that quantifies how well a material's degradation rate aligns with a target tissue's healing time
- Visualizes match scores across all material-tissue pairings as an interactive heatmap
- Renders an interactive 3D pore distribution model for each material

## Why I built it
Scaffold degradation rate needs to match tissue healing time — different rates can cause scaffold collapses and trigger inflammation. Graphing makes the comparison visible. 

## Tissues modeled
Skin, Cartilage, Bone, Cardiac Muscle, Tendon, Nerve, Liver

## How to run it
Open the `.ipynb` file in JupyterLab or VS Code with the Jupyter extension. Required libraries:
- numpy
- matplotlib
- ipywidgets

## Author
Sami Mohammed - Bioengineering, Temple University
