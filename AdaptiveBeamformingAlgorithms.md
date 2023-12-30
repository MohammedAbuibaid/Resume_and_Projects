### Comparison of Adaptive Beamforming Algorithms

#### Overview
This project involves a MATLAB script designed for simulating different adaptive beamforming algorithms. The key algorithms explored are:

- Constant Modulus (CM)
- Least Mean Squares (LMS)
- Normalized LMS
- Recursive Least Square (RLS)

The script dynamically adjusts the weights of the antenna array to optimize received signal quality based on the selected algorithm.

#### Performance Analysis
The script conducts a comprehensive analysis of the adaptive beamforming algorithm's performance. This includes:

- Bit Error Rate (BER) calculations
- Visualization of the beam pattern of the antenna array

These features provide an in-depth understanding of the algorithms' effectiveness.

#### Experiment Setup
The experiment is configured with the following setup:

- A transmitter emitting a QPSK-modulated signal
- Two interfering signals
- A receiver equipped with a uniform linear array (ULA) of antennas

The script simulates the performance of the beamforming algorithms under various signal-to-noise ratios (SNR), offering insights into their real-world applicability.

#### Results
Key outputs of the script include:

- Demodulation of the received signal
- Calculation of Bit Error Rate (BER) for selected SNR values
- Generation of plots such as:
  - BER performance over different SNRs
  - Error amplitude and phase of error
  - Convergence of the weight vector

These results are crucial for evaluating the effectiveness of each beamforming algorithm.

#### Additional Resources
For a more detailed overview, including visual aids, refer to the presentation slides linked below:

[Adaptive Beamforming Algorithms - Slide Presentation](https://www.slideshare.net/M_A_Abuibaid/adaptive-beamforming-algorithms-116173636)
