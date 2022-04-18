## Detecting potentiation with SPM

This repository holds source files for a 2021-22 study on detecting and quantifying post-activation twitch potentiation with statistical parametric mapping (SPM).
See the `src` directory for source code and the file `doc/analysis-overview.md` for an overview of the analysis steps leading from raw data to final product.

### Abstract 

This study proposes and demonstrates in practice the use of statistical parametric mapping (SPM) for reliably detecting and quantifying post-activation twitch potentiation in superficial skeletal muscles.
The study applies SPM to tensiomyographic measurements of the rectus femoris muscle's contractile response during electrically-induced twitch contraction following an incline squat conditioning exercise. SPM was found to reliably and quantitatively differentiate between the muscle's pre-conditioning and post-conditioning response, indicating the presence of post-activation potentiation.
More so, because SPM preserves the time-domain information contained in the original muscle response, SPM also gives an indication of *when* the potentiation-like state occurred over the course of the muscle twitch.

### Dependencies

Data analysis is performed in Python 3 with the help of the following libraries:

- [NumPy](https://numpy.org/): "the fundamental package for scientific computing with Python"
- [SciPy](https://scipy.org/): for statistical routines
- [Matplotlib](https://matplotlib.org/): for data visualization
- [Pandas](https://pandas.pydata.org/): for manipulation of tabular CSV and XLSX data
- [SPM1D](https://spm1d.org/): for statistical parametric mapping
- [TMG-Biomechanics](https://github.com/ejmastnak/tmg): for time series analysis of tensiomyography measurements
