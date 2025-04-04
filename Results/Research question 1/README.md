# Inputs
The inputs folder contains the web app graphs used in the experiments for Research Question 1.
### Unweighted
In the unweighted case, the strength of relationships is not considered. Therefore, all edges in the web app graph are assigned a uniform weight of 1.
||Value|
|:--:|:--:|
|w<sub>low</sub>|1|
|w<sub>mid</sub>|1|
|w<sub>high</sub>|1|

### Weighting mechanism proposed by study [[1](../../README.md#reference)]
In this case, stronger relationship types are assigned higher weights, which increase exponentially from 1 to 4 based on their strength.
||Value|
|:--:|:--:|
|w<sub>low</sub>|2<sup>0</sup>|
|w<sub>mid</sub>|2<sup>1</sup>|
|w<sub>high</sub>|2<sup>2</sup>|