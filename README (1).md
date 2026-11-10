# Quantum Tunneling Problem Solver

## Project overview
A Python/Jupyter Notebook simulation that estimates the probability of a particle tunneling through a one-dimensional potential barrier using the thick-barrier approximation.

## Objectives
- Select an electron, proton, or custom-particle option.
- Convert energy and length values into SI units.
- Calculate the wave number, decay constant, transmission probability, and reflection probability.
- Visualize the potential barrier, wavefunction, probability density, and transmission trends.

## Requirements
- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook (or JupyterLab)

Install dependencies:
```bash
pip install numpy matplotlib notebook
```

## Run the project
1. Clone or download this repository.
2. Open a terminal in the repository folder.
3. Start Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `Untitled0.ipynb`.
5. Run all cells.

## Default demonstration
The notebook currently demonstrates an electron with energy 1.0 eV, a barrier height of 2.0 eV, and a barrier width of 0.5 nm. The program uses fixed demonstration values in the current version.

## Model note
Transmission is estimated using `T = exp(-2 * kappa * width)` (thick-barrier approximation), and reflection is set to `R = 1 - T`. The plotted wavefunction is an illustrative construction and is not a full boundary-matched solution for a finite rectangular barrier. The custom-particle branch currently uses the electron mass as its default.

## Repository contents
- `Untitled0.ipynb` — source notebook.
- `README.md` — project information and run instructions.
- `outputs/` — optional exported plots.
- `RollNumber_Name_ProjectReport.pdf` — final report (rename after entering student details).
