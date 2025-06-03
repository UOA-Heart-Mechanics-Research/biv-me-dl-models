<div align="center">

# Deep learning models for biv-me

</div>

## v1.1 (current version)
### View selection model (ResNet50)

Developed with 418 cases
-   **[UK Biobank](https://www.ukbiobank.ac.uk/)**: 200
    -   Healthy
    -   Siemens (1.5T)
-   **[CARDIOHANCE](https://doi.org/10.3389/fcvm.2022.1016703)**: 160
    -   Mixed healthy/pathological
    -   Siemens (1.5T/3T)
-   **[CAP CHD](https://capchd.ucsd.edu/)**: 58
    -   Repaired Tetralogy of Fallot (rToF)
    -   GE, Philips (1.5T)

Number of classes: 10
-   SAX (short-axis of the ventricles)
-   SAX-atria (short-axis of the atria)
-   2ch (two chamber)
-   3ch (three chamber)
-   4ch (four chamber)
-   RVOT (right ventricular outflow tract)
-   RVOT-T (tranverse right ventricular outflow tract)
-   LVOT (left ventricular outflow tract)
-   2ch-RT (right sided two chamber)
-   Other (short axis with no cardiac structures)

### Segmentation models (3D nnU-Net)

Developed with 157 cases
-   **[UK Biobank](https://www.ukbiobank.ac.uk/)**: 70
    -   Healthy
    -   Siemens (1.5T)
-   **[CARDIOHANCE](https://doi.org/10.3389/fcvm.2022.1016703)**: 69
    -   Mixed healthy/pathological
    -   Siemens (1.5T/3T)
-   **[CAP CHD](https://capchd.ucsd.edu/)**: 18
    -   Repaired Tetralogy of Fallot (rToF)
    -   GE, Philips (1.5T)

#### SAX
-   LV cavity
-   LV myocardium
-   RV cavity
-   RV myocardium

#### 2ch
-   LV cavity
-   LV myocardium
-   LA cavity

#### 3ch
-   LV cavity
-   LV myocardium
-   RV cavity
-   LA cavity
-   Aorta
-   RV myocardium

#### 4ch
-   LV cavity
-   LV myocardium
-   RV cavity
-   LA cavity
-   RA cavity
-   RV myocardium

#### RVOT
-   RV cavity
-   RV myocardium
-   Pulmonary artery

## v1.0 (superseded)
### View selection model (ResNet50)

Developed with 360 cases
-   **[UK Biobank](https://www.ukbiobank.ac.uk/)**: 200
    -   Healthy
    -   Siemens (1.5T)
-   **[CARDIOHANCE](https://doi.org/10.3389/fcvm.2022.1016703)**: 160
    -   Mixed healthy/pathological
    -   Siemens (1.5T/3T)

Number of classes: 10
-   SAX (short-axis of the ventricles)
-   SAX-atria (short-axis of the atria)
-   2ch (two chamber)
-   3ch (three chamber)
-   4ch (four chamber)
-   RVOT (right ventricular outflow tract)
-   RVOT-T (tranverse right ventricular outflow tract)
-   LVOT (left ventricular outflow tract)
-   2ch-RT (right sided two chamber)
-   Other (short axis with no cardiac structures)

### Segmentation models (3D nnU-Net)

Developed with 100 cases
-   **[UK Biobank](https://www.ukbiobank.ac.uk/)**: 52
    -   Healthy
    -   Siemens (1.5T)
-   **[CARDIOHANCE](https://doi.org/10.3389/fcvm.2022.1016703)**: 48
    -   Mixed healthy/pathological
    -   Siemens (1.5T/3T)

#### SAX
-   LV cavity
-   LV myocardium
-   RV cavity
-   RV myocardium

#### 2ch
-   LV cavity
-   LV myocardium
-   LA cavity

#### 3ch
-   LV cavity
-   LV myocardium
-   RV cavity
-   LA cavity
-   Aorta
-   RV myocardium

#### 4ch
-   LV cavity
-   LV myocardium
-   RV cavity
-   LA cavity
-   RA cavity
-   RV myocardium

#### RVOT
-   RV cavity
-   RV myocardium
-   Pulmonary artery
