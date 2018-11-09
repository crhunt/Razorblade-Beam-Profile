# Razorblade-Beam-Profile
A little jupyter notebook for calculating a gaussian fit to a beam profile measured with the razor blade method

Requires:
scipy, numpy, matplotlib

The razor blade method: 
- Direct laser beam to a power meter. 
- In front of the power meter, mount a beam block ("razor blade") onto a micrometer stage such that the full beam can be blocked or exposed by moving the micrometer through its range.
- Increment the micrometer in equal steps, recording the power reading at each step (this is your input, ydata).

The program calculates the derivative of the integrated power to retrieve the beam profile. It fits the profile to a gaussian, plots both the profile and fit, and reports the fit parameters and the beam waist (FWHM).
