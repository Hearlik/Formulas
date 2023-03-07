# Alcohol-Equation 1

$$ {RS}_{actual} = 0.1808 * Plato + 0.8192 * {RS}_{apparent} $$

$$ {ABW}_{ferm} = {Plato - {RS}_{actual} \over 2.0665 - 0.010665 * Plato} $$

$$ {ABV}_{ferm} = {1 \over 0.795} * {ABW}_{ferm} $$

$$ {ABV}_{total} = {ABV}_{ferm} + {ABV}_{carbonation} $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| Plato | °P | density of the beer wort |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| ${RS}_{actual}$ | °P | actual residual sugar |
| ${ABV}_{ferm}$ | Vol% | Alcohol through the main fermentation |
| ${ABV}_{carbonation}$ | Vol% | Alcohol added through the carbonation |
| ${ABV}_{total}$ | Vol% | |


# Apparent attenuation

$$ A_{apparent} = {1 - {RS}_{apparent} \over Plato} * 100 $$

$$ A_{actual} = {1 - {RS}_{actual} \over Plato} * 100 $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| $A_{apparent}$ | % | apparent attenuation of the yeast |
| ${RS}_{actual}$ | °P | actual residual sugar |
| $A_{actual}$ | % | actual attenuation |


# Alcohol-Equation 2

$$ {RS}_{apparent} = \left( 1 - \left( {A_{apparent} \over 100} \right) \right) * Plato $$

$$ {RS}_{actual} = 0.1808 * Plato + 0.8192 * {RS}_{apparent} $$

$$ {ABV}_{ferm} = {1 \over 0.795} * \left( Plato - {RS}_{actual} \right) * {1 \over 2.0665 - 0.010665 * Plato} $$

$$ {ABV}_{total} = {ABV}_{ferm} + {ABV}_{carbonation} $$

| Variable | Unit | Description |
| :---: | :---: | --- |
| $A_{apparent}$ | % | apparent attenuation of the yeast |
| Plato | °P | density of the beer wort |
| ${RS}_{apparent}$ | °P | apparent residual sugar |
| ${RS}_{actual}$ | °P | actual residual sugar |
| ${ABV}_{ferm}$ | Vol% | Alcohol through the main fermentation |
| ${ABV}_{carbonation}$ | Vol% | Alcohol added through the carbonation |
| ${ABV}_{total}$ | Vol% | |
