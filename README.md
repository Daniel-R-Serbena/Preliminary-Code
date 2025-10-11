# Preliminary Code intended for X LASCON Participants Selection Evaluation.
These codes are still under validation and construction. License & Use. This repository is provided under an Evaluation-Only License for LASCON reviewers. No redistribution, modification, or reuse is permitted.

Both of this computational models represents a monosynaptic spinal reflex and polysynaptic circuits. The former pathways is sensory -> motor neurons, and latters, sensory -> interneuron -> motor neurons.
The two scripts features:

**Neuron models**: Conductance-based LIF with synaptic reversal potentials

**Synaptic dynamics**: Alpha-kernel temporal profiles with axonal delays

**Motor pool**: Two-compartment neurons (soma + dendrite) with dendritic nonlinearities

**Circuit types**: Monosynaptic (sensory→motor) and polysynaptic (sensory→interneuron→motor)

**Analysis**: Information transfer quantified via kNN mutual information (KSG estimator)
