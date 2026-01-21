# Notebook Review Checklist

## Critical fixes

- [ ] Update the adaptive relaxation in the interactive campaign so `current_omega` is passed into `config['omega_sor']` instead of the constant `OMEGA_SOR`.
- [ ] Decide which batch/campaign sections are meant to run by default in a notebook session; move the rest into functions or guard with explicit flags to avoid accidental long runs.

## Validation and correctness

- [ ] Add a small, fixed validation suite (2-3 cases) and compare `Nu`/`Sh` against the reference paper or trusted benchmarks.
- [ ] Confirm boundary-condition intent for the adiabatic case (top/bottom for `theta`, and whether `C` should be purely adiabatic or Soret-coupled) and align implementation + writeup.
- [ ] For porous cases near 0/180 degrees, record which runs diverge and confirm this matches expected stability behavior.

## Reproducibility and outputs

- [ ] Standardize where outputs are written (`simulation_results`, `campaign_results`, `results/raw_fields`) and document which cell writes what.
- [ ] Include a quick summary table cell that collects the most important runs for the report (case, grid, Ra, angle, BC, Nu, Sh, iterations, runtime).

## Documentation and presentation

- [ ] Add a brief “How to run” section describing the intended execution order and which sections are optional.
- [ ] Add a short “Assumptions” list (Boussinesq, steady-state, 2D, numerical scheme, convergence criteria) for the report.

## LaTeX Document 

- [] Make an option to save all the plots (organized somehow)
- [] Make a simple LaTeX document that only shows the results, very minimum explanation and derivations.