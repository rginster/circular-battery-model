# Circular Battery Production — System Dynamics Model

An interactive, self-contained system dynamics model of circular battery production,
covering 2000–2050. It links the market diffusion of battery electric vehicles with the
resulting battery and lithium demand, the recovery of material from end-of-life batteries,
their continued use in 2nd-life applications, and the resulting greenhouse gas emissions
(cradle-to-gate) of battery production.

**Live version:** <https://rginster.github.io/circular-battery-model/>

## Contents

`index.html` is the entire application: HTML, CSS and JavaScript in one file, with no
external resources, libraries or network access. Open it in any browser, or serve it from
any static host. It works offline and on mobile.

## Features

- Five scenarios plus five adjustable parameters (battery capacity, battery lifetime,
  recycling efficiency, share going to 2nd life, 2nd-life lifetime)
- Nine result charts with hover readout, keyboard stepping and a table view per chart
- Interactive stock-and-flow diagram: click any element for its equation, unit and causal links
- Full documentation of equations, parameters, time series and model assumptions
- English and German interface (English by default), light and dark colour scheme
- CSV export of all result series and PNG export per chart

## Model

Offline reimplementation of the Insight Maker model *Zirkuläre Batterieproduktion* by
Raphael Ginster. Structure, equations, units, time series and scenarios were adopted
unchanged; the key figure overview, scenario comparison, table and export views and the
comparison with empirical fleet data were added.

## Sources

- Ginster, R., Blömeke, S., Popien, J. L., Scheller, C., Cerdas, F., Herrmann, C., &
  Spengler, T. S. (2024). Circular battery production in the EU. *Journal of Industrial
  Ecology*, 28, 1165–1182. doi:10.1111/jiec.13527
- European Alternative Fuels Observatory — Vehicles and fleet, Germany.

## Funding

Research Training Group CircularLIB, funded by the Ministry for Science and Culture of
Lower Saxony from the zukunft.niedersachsen programme of the Volkswagen Foundation
(grant number MWK|ZN3678).
