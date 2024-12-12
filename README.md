# Ensemble_model
**Folders:**
- **reflectance_spectra_training&validation**: This folder has raw data of the olivine, pyroxene, olivine-poyroxene mixtures, and Ocs reflectance spectra. First raw give the name of he sample. First column 'W' is wavelength in um and the second column is reflectance.
**Files:**
- **input_data.xlsx:** contains 169 selected data for the training and validation of the model. reflectance spectra of each sample were interpolated to a uniform range of 550–2250 nm and denoised using Gaussian filtering (σ = 7 nm). The interpolation was performed at fixed wavelength intervals of 50-nm interval. All the spectra were normalized at 550 nm. The last column indicates the irradiation type (1- olivine with H ion irradiation, 2- pyroxene with H ion irradiation, 3- olivine-pyroxene mixtures and OCs with H ion irradiation, 10- olivine with laser irradiation,11- pyroxene with laser irradiation, 12- olivine-pyroxene mixtures and OCs with laser irradiation ). 
- **data_all_H_laser.xlsx:** includes the exposure time for the training and validation data and the details of the samples (relevant article, sample type, irradiation method, etc.). This only includes the selected samples based on the criteria mentioned in the palamakumbure.et al.2025.
- **asteroid_spectra.xlsx:** reflectance spectra of asteroids. 
