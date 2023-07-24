# AutoGHGenius
The current files serve as a proof of concept for the automation of GHGenius to execute multiple model runs for different regions, store and compile the results, and produce a single carbon intensity figure for the calculation.  The current version should not be taken as accurate; it is run with default information with the exception of setting the Region for each run, and setting the year to 2024.  The fuel has been set to Refined Bio Oil from Wood Residue; other Fuel / Feedstock combinations may not be supported.

To Do:
- Add emissions from fuel use to the calculation.
- Incorporate user-provided transportation methods and distances into the model.
- Verify support for other combinations of Fuels / Feedstocks.
- Allow energy and feedstock inputs distinct from the defaults provided by GHGenius.
