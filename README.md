# V2V
This project simulates various aspects of wireless communication channels, specifically focusing on vehicle-to-vehicle (V2V) scenarios. It uses the sum-of-sinusoids method to generate simulated Gaussian processes, which are fundamental building blocks for modeling fading channels.

Here's a breakdown of the project by tasks:

Task 3: Generates four independent Gaussian processes (x1, y1, x2, y2) using the sum-of-sinusoids method and plots their probability density functions (PDFs). These simulated PDFs are compared against the theoretical Gaussian PDF to validate the generation method.
Task 4: Computes and plots the autocorrelation functions (ACFs) of the generated Gaussian processes. It compares the simulated ACFs with the theoretical ACF based on Clarke's model, a common model for mobile radio channels. This task also explores the effect of different numbers of sinusoids (N) and adding noise on the ACF.
Task 5: Combines the four Gaussian processes (x1, y1, x2, y2) to simulate the in-phase (x) and quadrature (y) components of a V2V channel. It plots the PDFs of these components and compares them to the theoretical Laplacian PDF, which is expected for the product of two independent Gaussian random variables.
Task 6: Calculates the envelope (R) and channel power gain (Omega) from the simulated in-phase and quadrature components (x and y). It then plots the PDFs of R and Omega and compares them to their respective theoretical distributions, which are related to the modified Bessel function of the second kind.
Task 7: Computes and plots the phase (theta) of the simulated V2V channel. The simulated phase PDF is compared to the theoretical uniform distribution, which is characteristic of the phase of a complex Gaussian process.
Task 8: Computes and plots the ACFs of the simulated in-phase and quadrature components (x and y) of the V2V channel. These are compared against the theoretical ACFs, which involve the product of two Bessel functions.
Task 9/b: This task focuses on the bit error rate (BER) performance in different fading conditions (slow and fast fading). It plots the theoretical BER curves against the average signal-to-noise ratio (SNR) for these two scenarios.
In essence, this project explores the statistical properties of simulated V2V fading channels, including their PDFs, ACFs, envelope, power gain, and phase distributions, and compares these simulations to theoretical models commonly used in wireless communications.
