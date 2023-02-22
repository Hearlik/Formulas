# IBU-Formula

$$ {IBU}_i = {m_i * \alpha_i * 10 * {1 \over V}} * \left( 1 - e^{-0.04 * \left( t_{i, boiling} + {ISO_{coeff}} \right)} \right) * 1.65 * 0.000125^{0.004 * Plato} * c_{time} * c_{type} $$

$$ {IBU}_{total} = \sum_{i=1}^n {IBU}_i $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| $m_i$ | kg | amount of hop i |
| $\alpha_i$ | % | $\alpha$-Acid of hop i |
| V | L | Volume of the beer wort |
| Plato | °P | density of the beer wort |
| $t_{i, boiling}$ | min | boiling time of hop i |
| ${ISO_{coeff}}$ | min | extension factor to the regular boiling time |
| $c_{time}$ | | time factor = $\left(t_{i, boiling} < t_{boiling, total} - 15 min \right)$ ? 1.1 : 1.0 | 
| $c_{type}$ | | type factor = 1.1 if hop pellets , 1.0 if hop cones |

### Isomerisation-coefficient

$$ {ISO_{coeff}} = t_{ISO} * 0.046 * e^{0.031 * T_{end}} $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| $t_{ISO}$ | min | total time of the Isomerisation |
| $T_{end}$ | °C | Temperature at the end of the Isomerisation |

# Bitterness table

| ${IBU_{total} \div Plato}$ | perceived bitterness |
| :---: | :---: |
| $< 1.0$ | very mild |
| $[1.0, 1.5)$ | mild |
| $[1.5, 2.5)$ | balanced |
| $[2.5, 3.0)$ | bitter |
| $\geq 3.0$ | very bitter |
