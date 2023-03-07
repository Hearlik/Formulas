# Alcohol-Formula 1

$$ {RS}_{actual} = 0.1808 * Plato + 0.8192 * {RS}_{apparent} $$

$$ {Alcohol}_{ferm} \left[ Weight\% \right] = {Plato - {RS}_{actual} \over 2.0665 - 0.010665 * Plato} $$

$$ {Alcohol}_{ferm} \left[ Vol\% \right] = {1 \over 0.795} * {Alcohol}_{ferm} \left[ Weight\% \right] $$

$$ {Alcohol}_{total} = {Alcohol}_{ferm} + {Alcohol}_{carbonation} $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| ${RS}_{actual}$ | °P | actual residual sugar |
| Plato | °P | density of the beer wort |
| ${Alcohol}_{total}$ | Vol% or Weigth% | |
| ${Alcohol}_{carbonation}$ | Vol% or Weigth% | Alcohol added through the carbonation |


# Apparent attenuation

$$ A_{apparent} = {1 - {RS}_{apparent} \over Plato} * 100 $$

$$ A_{actual} = {1 - {RS}_{actual} \over Plato} * 100 $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| $A_{apparent}$ | % | apparent attenuation of the yeast |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| $A_{actual}$ | % | actual attenuation |
| ${RS}_{actual}$ | °P | actual residual sugar |


# Alcohol-Formula 2

$$ {RS}_{apparent} = \left( 1 - \left( {A_{apparent} \over 100} \right) \right) * Plato $$

$$ {RS}_{actual} = 0.1808 * Plato + 0.8192 * {RS}_{apparent} $$

$$ {Alcohol}_{total} = {1 \over 0.795} * \left( Plato - {RS}_{actual} \right) * {1 \over 2.0665 - 0.010665 * Plato} + {Alcohol}_{carbonation} $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| $A_{apparent}$ | % | apparent attenuation of the yeast |
| Plato | °P | density of the beer wort |
| ${RS}_{actual}$ | °P | actual residual sugar |
| ${Alcohol}_{total}$ | Vol% | |
| ${Alcohol}_{carbonation}$ | Vol% | Alcohol added through the carbonation |
