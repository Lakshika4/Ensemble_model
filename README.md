# Ensemble_model
**Folders:**
- **reflectance_spectra_training&validation**: This folder has raw data of the olivine, pyroxene, olivine-poyroxene mixtures, and Ocs reflectance spectra. First raw give the name of the sample. The first column 'W' is wavelength in um and the second column is reflectance.
- **Python_scripts**
  - This folder contains python scripts for,
    - Ensemble_model_validation.ipynb - Ensemble model training and validation
    - Ensemble_model_training.ipynb - saves 30 Ensemble models in .joblib
    - Surface_age_determination.ipynb - Determine the surface of asteroids
 - **Models**
  30 models in ".joblib" format saved after model training
- **results**
  - En_validation_results.xlsx - Results from the Ensemble model validation.
  - predictios_results_H_and_L.xlsx - Asteroid surface age predicted using the Ensemble method at 1 AU. This included values for all 30 iterations,
  - Surface_age_asteroids.xlsx - Asteroid surface age determined by the Ensemble model at 1 AU and the corrected surface age of asteroids.

**Files:**
- **requirments.txt**
List of packages and their version.
- **input_data.xlsx:** contains 169 selected data for the training and validation of the model. reflectance spectra of each sample were interpolated to a uniform range of 550–2250 nm and denoised using Gaussian filtering (σ = 7 nm). The interpolation was performed at fixed wavelength intervals of 50-nm interval. All the spectra were normalized at 550 nm. The last column indicates the irradiation type (1- olivine with H ion irradiation, 2- pyroxene with H ion irradiation, 3- olivine-pyroxene mixtures and OCs with H ion irradiation, 10- olivine with laser irradiation,11- pyroxene with laser irradiation, 12- olivine-pyroxene mixtures and OCs with laser irradiation ). 
- **data_all_H_laser.xlsx:** includes the exposure time for the training and validation data and the details of the samples (relevant article, sample type, irradiation method, etc.). This only includes the selected samples.
- **asteroid_spectra.xlsx:** reflectance spectra of asteroids. 
