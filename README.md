# Leaky Integrate-and-Fire (LIF) Spiking Neural Network Simulation

## Objective
This project simulates the electrical dynamics of a biological neural circuit from first principles. By modeling a population of neurons based on established biophysical parameters, the project visualizes how neural networks process background synaptic noise and reach action potential thresholds.

## Methodology
* **Circuit Modeling:** Utilized the `Brian2` neuro-simulation framework to construct a network of 100 Leaky Integrate-and-Fire (LIF) neurons. 
* **Biophysical Parameters:** Programmed established biological constants, including a resting membrane potential of -70mV, a firing threshold of -50mV, and incorporated Poisson-distributed noise to simulate background synaptic input from external brain regions.
* **Visualization:** Generated raster plots to visualize population-level spike timing and plotted individual membrane voltage traces using `matplotlib` to observe subthreshold dynamics and action potential generation.

## Significance
This simulation highlights a strong foundation in computational neuroscience and dynamical systems, demonstrating the ability to translate biophysical differential equations into functional code to model live brain circuitry.
