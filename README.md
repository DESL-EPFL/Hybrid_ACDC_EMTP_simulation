# Hybrid-AC-DC-grid

We provide an EMTP-RV model of a hybrid low-voltage AC/DC grid. The AC grid (identical to the CIGREE low-voltage distribution grid) is coupled using 4 voltage source converters to an 8 node DC grid. Two simulations are provided: one model that includes a exact switching VSC model and one that uses a average VSC model. The simulations are used for the validation of a linear state estimation algorithm for hybrid AC/DC micro grids [1].

## Files

[Hybrid-AC-DC_microgrid-Average-model.ecf] Model that uses an average VSC model
[Hybrid-AC-DC_microgrid-Switching-model.ecf] Model that uses an exact switching VSC model


## Software
The following software is required to run the model:

EMTP-RV (https://www.emtp.com/) The models are ran both on V4.1 and V4.2 

[1] reference will be published soon. For more info contact the author at willem.lambrichts@epfl.ch

