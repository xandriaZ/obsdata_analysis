# Astronomical Data Reduction and Analysis

This repository showcases a series of observational astronomy projects completed as part of the **Observational Experiments of Astrophysics** course (AY2025/26 Semester 1). The projects focus on the complete workflow of astronomical data analysis, from raw CCD observations to scientifically meaningful results.

The notebooks demonstrate practical experience with astronomical image reduction, photometric measurements, flux calibration, and stellar population analysis using Python and modern astronomical data analysis tools.

---


## Project Structure

### `1_calibration.ipynb`

A complete CCD reduction workflow demonstrating the creation and application of master bias, dark, and flat-field frames.

**Techniques used**

* CCD calibration
* Image preprocessing
* Noise and artifact removal
* Data quality assessment

### `M33_fluxcalib_phot.ipynb`

Photometric and flux-calibration analysis of observations of the Triangulum Galaxy (M33).

**Techniques used**

* Aperture photometry
* Background subtraction
* Magnitude determination
* Flux calibration
* Scientific image analysis

### `M15_HRdiagram.ipynb`

Construction and analysis of a Hertzsprung–Russell diagram for the globular cluster M15.

**Techniques used**

* Multi-band photometric analysis
* Color–magnitude diagram construction
* Stellar population studies
* Evolutionary sequence identification

---

## Software and Libraries

The analysis is performed using the Python scientific ecosystem, including:

* NumPy
* Matplotlib
* Astropy
* Photutils
* SciPy
* Pandas

---

## Scientific Workflow

The projects collectively follow a typical observational astronomy pipeline:

1. Acquisition of raw CCD observations
2. Instrumental calibration and image reduction
3. Source detection and photometric measurements
4. Flux and magnitude calibration
5. Scientific interpretation of processed data

---

## Key Skills Demonstrated

### CCD Data Reduction

Implementation of a standard CCD image processing pipeline:

* Bias frame combination and subtraction
* Dark current correction
* Flat-field calibration
* Generation of master calibration frames
* Reduction of raw science images

These procedures remove instrumental artifacts and prepare observational data for scientific analysis.

### Photometric Analysis

Extraction of brightness information from astronomical images:

* Source identification
* Aperture photometry
* Sky background estimation
* Instrumental magnitude measurements
* Photometric calibration

The analysis converts detector counts into calibrated measurements suitable for scientific interpretation.

### Flux Calibration

Transformation of instrumental measurements into physical quantities:

* Calibration using reference sources
* Determination of calibration coefficients
* Flux conversion and scaling
* Quantitative comparison between observations and standards

### Stellar Population Analysis

Investigation of stellar systems through photometric observations:

* Multi-band photometric processing
* Color index calculation
* Construction of color–magnitude diagrams
* Hertzsprung–Russell (HR) diagram analysis
* Identification of stellar evolutionary sequences

---

## Research Relevance

These projects provide hands-on experience with techniques commonly used in observational astrophysics research. The workflows implemented here mirror the fundamental steps required to transform raw telescope data into scientifically useful measurements and to investigate the physical properties of astronomical objects.

The repository highlights practical skills in:

* Astronomical data reduction
* Observational data analysis
* Photometric techniques
* Scientific programming with Python
* Reproducible research workflows




