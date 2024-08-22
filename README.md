This is a simple code in Tikz intended to draw the Kepler problem trajectories for a pair of masses. The input parameters are the values of the masses, the angular momentum, and the impact parameter. The plot is precise, but the distances are not because the code neglects the role of Newton's constant G, which ends up being equivalent to a scaling in the radius. The code can be used to plot trajectories involving negative masses, as long as the two masses are not opposite (same magnitude with different signs).

This code was inspired by the work of Shatskiy, Novikov, and Kardashev[^1].

[^1]: Shatskiy, A. A., I. D. Novikov, and N. S. Kardashev, "The Kepler Problem and Collisions of Negative Masses", [_Physics-Uspekhi_ **54**, 381 (2011)](https://doi.org/10.3367/UFNe.0181.201104e.0399).
