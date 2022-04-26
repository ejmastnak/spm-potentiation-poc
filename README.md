## Detecting potentiation with SPM

This repository holds source files for a 2021-22 study on detecting and quantifying post-activation twitch potentiation with statistical parametric mapping (SPM).
See the `src` directory for source code and the file `doc/analysis-overview.md` for an overview of the analysis steps leading from raw data to final product.

### About 

This study proposes and demonstrates in practice the use of statistical parametric mapping (SPM) for reliably detecting and quantifying post-activation twitch potentiation in superficial skeletal muscles.
The study applies SPM to tensiomyographic measurements of the rectus femoris muscle's contractile response during electrically-induced twitch contraction following an incline squat conditioning exercise. SPM was found to reliably and quantitatively differentiate between the muscle's pre-conditioning and post-conditioning response, indicating the presence of post-activation potentiation.
More so, because SPM preserves the time-domain information contained in the original muscle response, SPM also gives an indication of *when* the potentiation-like state occurred over the course of the muscle twitch.

### Project structure

Following is a one-sentence summary of each directory.
See the `README.md` file in each directory for more detailed descriptions.

- `data` holds the raw and processed measurement data files used in the study.
- `results` holds the results of all analysis performed in the study (e.g. SPM tests, TMG contraction parameters, figures).
- `src` holds the Python source code used to analyze the data.

### Analysis

See the `ANALYSIS.md` file for an overview of the full data analysis pipeline used in the study.

### License

The project source code, i.e. the contents of the `src` directory, is licensed under the GNU General Public License v3.0.
All other original content is licensed under the CC-BY 4.0 license.
