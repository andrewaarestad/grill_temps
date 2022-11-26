# grill_temps

Some code for estimating how long it will take to grill a piece of meat.

Usees a simple heat transfer model to predict target temp arrival based on measurements collected.  Fits the following model to measurement data:

```math
\frac{dT}{dt} = k(T_{meat} - T_{grill})
```

![Temp Projection Chart][projection.png]