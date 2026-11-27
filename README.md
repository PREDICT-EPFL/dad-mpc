# DAD-MPC

Disturbance-adaptive MPC (DAD-MPC): code (coming soon), and an interactive building-control game.

Disturbance-adaptive model predictive control (DAD-MPC) adjusts its constraint-tightening
margin online from its own record of constraint violations, so that the long-run average
violation rate stays below a user-chosen bound. In building climate control, this trades a
small, bounded amount of comfort violation for energy savings.

**Code:** coming soon.

## Play: Thermal Balloon
Keep a house warm through two winter days on your phone, and race a rule thermostat,
MPC, robust MPC and DAD-MPC.

**Play in your browser:** https://sjcszw.github.io/thermal-balloon/
(no install; English / 中文 / Français)

The game is a simplified teaching world; its numbers are not results from the papers below.

## References
1. J. Shi, C. Salzmann, C. N. Jones. [Disturbance-adaptive data-driven predictive control:
   trading comfort violation for savings in building climate control](https://doi.org/10.1109/TCST.2026.3664129).
   IEEE Transactions on Control Systems Technology, 2026.
2. J. Shi, C. N. Jones. [Disturbance-adaptive model predictive control for bounded average
   constraint violations](https://doi.org/10.48550/arXiv.2503.24169). 23rd IFAC World Congress, 2026.
3. J. Shi, C. N. Jones. [User-specified Kelvin-hour budgets within model predictive control for
   energy-efficient buildings: Simulation and field demonstration](https://doi.org/10.48550/arXiv.2609.06698).
   arXiv:2609.06698, 2026.

The game's house model is identified from data of the BOPTEST test case `bestest_hydronic_heat_pump`,
and its weather comes from the BOPTEST weather file: D. Blum, J. Arroyo, S. Huang, J. Drgoňa,
F. Jorissen, H. T. Walnum, Y. Chen, K. Benne, D. Vrabie, M. Wetter, L. Helsen.
[Building optimization testing framework (BOPTEST) for simulation-based benchmarking of control
strategies in buildings](https://doi.org/10.1080/19401493.2021.1986574).
Journal of Building Performance Simulation, 14(5):586–610, 2021.

## Copyright
© 2026 Jicheng Shi, PREDICT Lab, EPFL. All rights reserved.
