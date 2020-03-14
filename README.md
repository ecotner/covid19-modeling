# N-COV-19

Attempt at modeling the spread of the 2019 novel coronavirus.

## Discrete-time model
Simple model of the growth based on a discrete-time recurrence relation that takes into account nonlinear interactions between sick, well, immune, and dead populations, as well as a time-delay between infection and recovery/death. Parameters are fixed from the outset and are not fit to data, although they are chosen heuristically based on what we've seen so far. You can examine the [jupyter notebook](notebooks/discrete_time_model.ipynb) for more information.
