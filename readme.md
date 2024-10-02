NEURON mod files for the I-A current from the paper:
Beck H, Ficker E, Heinemann U.
Properties of two voltage-activated potassium currents in 
acutely isolated juvenile rat dentate gyrus granule cells.
J. Neurophysiol. 68, 2086-2099 (1992)

Running the kinetics.hoc simulation file will show 
the activation and inactivation steady-states, the time constants, 
and a family of curves generated modeling the same protocols 
used in the experiments for Figs.3A-3C of the paper.

According to this paper, the kinetic parameters change with
development. The values used in this model are those needed
to reproduce the experimental findings of Fig.3.

The time constants reported in the paper are shown
as markers of different color. 
Time constants in the range not covered by the paper
and activation kinetics have 
been adjusted to give a reasonable approximation of the
voltage-clamp current traces in Figs.3A-3C.
 
## Under unix systems:
to compile the mod files use the command 
``` nrnivmodl ```
and run the simulation hoc file with the command 
``` nrngui kinetics.hoc```

## Under Windows using NEURON 5.1:
to compile the mod files use the ``` mknrndll ``` command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

\
Questions on how to use this model should be directed to
michele.migliore@pa.ibf.cnr.it
