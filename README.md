# changing-bc-natural-convection

Research workspace for exploring changing boundary conditions in natural convection, with related analytical and computational experiments.

## Contents

- `peristaltic-flow/`: peristaltic flow work in an elliptic duct.
- `peristaltic-flow/code/nadeem-verification.ipynb`: verification notebook for Nadeem et al. (2022) mixed convection with heat and mass transfer.
- `porous-media-convection-darcy-benard/`: Darcy-Benard porous media convection exploration.
- `porous-media-convection-darcy-benard/code/darcy-main.ipynb`: primary notebook for the Darcy-Benard setup.
- `natural-convection-enclosed/`: enclosed natural convection simulations and visuals.
- `natural-convection-enclosed/main.ipynb`: main notebook for enclosed natural convection experiments.
- `natural-convection-enclosed/visualizations.ipynb`: visualization notebook for enclosed natural convection.
- `outputs/`: generated figures, tables, or exports.
- `main-paper/`: draft materials for the main paper.
- `website/`: project site assets.
- `checklist.md`: running task checklist.

## Quick start
Open the notebook with Jupyter (or however you like to play with `.ipynb` files):
```bash
jupyter lab
```
Then open one of:
- `peristaltic-flow/code/nadeem-verification.ipynb`
- `porous-media-convection-darcy-benard/code/darcy-main.ipynb`
- `natural-convection-enclosed/main.ipynb`

## Requirements
Core Python packages used across the notebooks:
- `numpy`
- `matplotlib`
- `scipy`
- `numba`
- `pandas`

Install from `requirements.txt`:
```bash
pip install -r requirements.txt
```
