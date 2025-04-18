# pymc_cox_ph_notebook
cox proportional hazards implementation for pymc/pytensor

This repo simply contains a notebook that has an implementation of cox proportional hazards for pymc/pytensor.
The coverage of survival analysis in the pymc resources inspired this. I was unable to find any examples cox hp for pymc anywhere.
I also felt, in my opinion(as of the time of this writing), that existing pymc resources did not do censorship, as understood in survival analysis, justice. Either treating censored as living or being forced to use additional external loss functions(Pymc's Potential). I hope people find my work useful. I have purposefully not packaged up this code, allowing practitioners to adjust things as needed, or use this code as part of a greater model
