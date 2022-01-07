# Hybrid-AC-DC-grid

We provide an EMTP-RV model of a hybrid low-voltage AC/DC grid. The 18 node AC grid (identical to the CIGREE low-voltage distribution grid [1]) is coupled using 4 voltage source converters to an 8 node DC grid. Two simulations are provided: one model that includes a exact switching VSC model and one that uses a average VSC model. The simulations are used for the validation of a linear state estimation algorithm for hybrid AC/DC micro grids [2].
[Hybrid-AC-DC_microgrid-Switching-model_Model.pdf](https://github.com/DESL-EPFL/Hybrid-AC-DC-grid/files/7829242/Hybrid-AC-DC_microgrid-Switching-model_Model.pdf)
![Screenshot 2022-01-07 at 15 08 18 (2)](https://user-images.githubusercontent.com/57922986/148555762-e59ae22f-6194-4163-a142-9d90b0e97a44.png)


## Files

[Hybrid-AC-DC_microgrid-Average-model.ecf] Model that uses an average VSC model
[Hybrid-AC-DC_microgrid-Switching-model.ecf] Model that uses an exact switching VSC model


## Software
The following software is required to run the model:

EMTP-RV (https://www.emtp.com/) The models are work both on version V4.1 and V4.2 


[1] S. Barsali, K. Strunz, and Z. Styczynski, “Cigre’ task force c6.04.02: Developing benchmark models for integrating distributed energy resources,”
[2] reference will be published soon. For more info contact the author at willem.lambrichts@epfl.ch

