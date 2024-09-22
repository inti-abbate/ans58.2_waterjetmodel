ANSI/ANS 58.2-1988 Water Jet Model

This is an implementation of the ANSI/ANS 58.2-1988 water jet model,
for simulation of flashing discharge of initially subcooled water,
using the Henry-Fauske mass flux model.

Inputs are:
  * Initial stagnation pressure
  * Initial stagnation temperature
  * Ambient pressure
  * Pipe rupture diameter

Outputs are:
  * Critical mass flux (Henry-Fauske model)
  * Jet boundaries geometry
  * Impingement pressure distribution inside the jet
  * Isobar curves inside the jet

The implementation includes the following validation benchmarks:
  * NUREG/CR-7275 mass flux curves
  * NEI 04-07 Vol. 2 isobar curves
  * NEI 04-07 Vol. 2 curves of equivalent radii of ZOI (volume
    inside isobar surface).
