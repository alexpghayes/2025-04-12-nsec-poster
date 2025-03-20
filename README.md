# Estimating peer influence: limitations of linear-in-means model

Linear-in-means models are often used to investigate peer effects. Estimating peer effects in linear-in-means models requires care, as peer effects may be subject to the "reflection problem", an identification failure in the form of perfect collinearity. In many settings, well-known identification conditions guarantee that perfect collinearity is not an issue. However, these identifying conditions are not sufficient to guarantee that peer effects are estimable. Even when identifying conditions guarantee that peer effect terms are not collinear, peer effects can become increasingly collinear as sample size grows larger. We show that asymptotic collinearity occurs whenever nodal covariates
are independent of the network and the minimum degree of the network is growing. Asymptotic collinearity can cause estimates of peer effects to be inconsistent or to converge at slower than expected rates. We also show that dependence between nodal covariates and network structure can alleviate collinearity issues in random dot product graphs. These results suggest that linear-in-means models are less reliable for studying peer influence than previously believed.

## Poster preview

![](AlexHayes-NSEC2025.png)

## Converting from PDF to TIFF or PNG for printing on online display

```sh
magick -density 250 -quality 85 poster.pdf AlexHayes-NSEC2025.png
```