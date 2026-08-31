Hello, I am Theo, and this is my research on:

Title (working): A Reproducible Benchmark of GNC Architectures for Flexible Spacecraft Attitude Control Under Model, Sensor, and Disturbance Uncertainty.

Core research question: For a flexible spacecraft under realistic uncertainty, how do different estimator + controller combinations compare, and at which stage of the sensing → estimation → control pipeline does uncertainty cost the most pointing performance?

The contribution is the controlled attribution — one shared plant, blocks swapped one at a time, so a performance loss can be pinned to a specific stage. That's the framing that survives the literature (flexible-spacecraft MPC and EKF-vs-UKF are individually crowded; the controlled pipeline attribution on a shared model is not).