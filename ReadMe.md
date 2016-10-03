# Oefenen met Vega-Light 

## Visualisatie van Gemeente data met Gas verbruik

De data komt uit een simpele csv en wordt gevisualiseerd met Vega-Ligth. 

[Vega-Lite](https://vega.github.io/vega-lite/docs/) is a high-level visualization grammar. It provides a concise JSON syntax for supporting rapid generation of visualizations to support analysis. Vega-Lite can serve as a declarative format for describing and creating data visualizations. Vega-Lite specifications can be compiled to a lower-level, more detailed Vega specifications and rendered using Vega’s compiler.

[Have a look at the html!](nieneb.github.com/visualisatie_vega)


```vis
data:
  url: "gem_2016_data.csv"
mark: point
encoding:
  x:
    type: quantitative
    field: opp_land
  y:
    type: quantitative
    field: g_gas_tot_2010
```