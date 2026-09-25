# SINDy practice notebooks

Notebooks working through **SINDy** (Sparse Identification of Nonlinear Dynamics, Brunton, Proctor & Kutz 2016) from first principles, as groundwork for a thesis on multi-agent attrition dynamics.

- `learning_experiments/sindy_from_scratch.ipynb` — implements SINDy by hand (candidate library, least squares, sequential thresholding) on the Lotka–Volterra predator-prey system.
- `practice/SIR_epidemic_model.ipynb` — same from-scratch approach applied to the SIR epidemic model.
- `practice/lanchester_square_law.ipynb` — uses PySINDy to recover Lanchester's square law from force-size trajectories, clean vs. noisy, as the smallest version of the thesis's attrition-dynamics problem.
- `practice/data_driven_oscillator.ipynb` — recovers a linear first-order system driven by a known control input.
