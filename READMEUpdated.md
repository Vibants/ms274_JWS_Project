# ms274_JWS_Project
Repository for code in the ms274 project

Updating README file for November 23

# Draft of Final Project Manuscript

## Proposed Title

Remote Sensing of Environmental Variability and Its Implications 
for Juvenile White Shark (JWS) Habitat Availability in Monterey Bay, California

**Author:** Anthony McGinnis Jr.  
**Affiliation:** Moss Landing Marine Laboratories, California State University, Monterey Bay  
**Course:** MS 274 – Remote Sensing  
**Target Journal:** Marine Environmental Research  
**Target Word Count:** 4,500 words  

---

## Abstract

*Target: 250 words*

- Background and ecological significance.
- Research objectives.
- Remote sensing products and analytical methods.
- Interpretation of analysis.
- Ecological implications for juvenile white shark habitat availability.

**Keywords:** Juvenile white sharks; remote sensing; sea surface temperature; chlorophyll-a; thermal habitat; Monterey Bay; acoustic telemetry .

---

## 1. Introduction

*Target: 1,000 words*

### 1.1 Climate-Driven Changes in Marine Ecosystems

- Ocean warming and marine heatwaves.
- Climate-driven shifts in marine predator distributions.
- Environmental variability along the California coastline.

### 1.2 Juvenile White Shark Habitat Ecology

- Nearshore habitat use and nursery areas.
- Thermal preferences and physiological constraints.
- Environmental drivers of juvenile white shark distribution.
- Recent northward expansion into Monterey Bay.

### 1.3 Oceanographic Characteristics of Monterey Bay

- Seasonal coastal upwelling.
- Monterey Bay upwelling shadow.
- Nearshore thermal refugia.
- Seasonal variability in primary productivity.

### 1.4 Remote Sensing Applications in Marine Predator Ecology

- Satellite-derived sea surface temperature (SST).
- Sea surface temperature anomalies (SSTA).
- Chlorophyll-a concentration as an indicator of phytoplankton biomass.
- Applications and limitations of remotely sensed environmental data.

### 1.5 Research Objectives

1. Observe the spatial and temporal variability of sea surface 
temperature within Monterey Bay.

2. Assess this past summer's/fall changes in chlorophyll-a concentration within 
the nearshore environment.

3. Analyze environmental conditions that may contribute to potential
juvenile white shark fine-scale movement.

---

## 2. Materials and Methods

*Target: 1,500 words*

### 2.1 Study Area

- Monterey Bay, Central California.
- Seacliff State Beach and New Brighton State Beach.
- Regional oceanographic characteristics.
- Geographic boundaries of the study area.

### 2.2 Environmental Data Acquisition
- Remote sensed Chl-a data from https://www.oceancolour.org/portal/
- Remote sensed SST and SSTA from EarthData/NASA MURSST
- In-situ acoustic detection data

#### 2.2.1 Sea Surface Temperature

- Data source and satellite product.
- Spatial and temporal resolution.
- Geographic and temporal data selection.

#### 2.2.2 Sea Surface Temperature Anomalies

- NOAA ERDDAP data acquisition.
- MUR SST anomaly product.
- Reference climatology.
- Magnitude and persistence of thermal anomalies.

#### 2.2.3 Chlorophyll-a Concentration

- Copernicus Marine data acquisition.
- Product characteristics and data provenance.
- Spatial and temporal resolution.
- Chlorophyll-a concentrations in mg/m³.

### 2.3 Data Preprocessing

- NetCDF data extraction.
- Geographic subsetting.
- Missing-value identification and filtering.
- Temporal standardization.
- Environmental data quality control.

### 2.4 Spatial Analysis

- Spatial distributions of SST and chlorophyll-a.
- Identification of relatively warm nearshore waters.
- Spatial variability within Monterey Bay.
- Geographic visualization using Cartopy and QGIS.

### 2.5 Temporal Analysis

- Daily mean environmental conditions.
- Seasonal variability.
- Magnitude and persistence of temperature anomalies.
- Temporal relationships between SST and chlorophyll-a.

### 2.6 Statistical Analysis

- Basic mean Chl-a, SST, and SSTA stats.
- Environmental comparisons.
- Correlation between environmental variables and study species.
- Evaluation of temporal autocorrelation and missing observations.

### 2.7 Data Visualization and Reproducibility

- Python and JupyterLab.
- NumPy, Matplotlib, NetCDF4, moviepy, and Cartopy.
- QGIS spatial visualization.
- Reproducible data acquisition notebooks.
- GitHub repository for storing code and figures.

---

## 3. Results

*Target: 600 words*

### 3.1 Spatial Distribution of Thermal Conditions

- Spatial variability in sea surface temperature.
- Distribution of relatively warm nearshore waters.
- Environmental conditions surrounding the study area.

### 3.2 Temporal Variability in Sea Surface Temperature

- Seasonal temperature patterns.
- Positive and negative SST anomalies.
- Timing, magnitude, and duration of warm-water conditions.

### 3.3 Temporal Variability in Chlorophyll-a Concentration

- Seasonal patterns in chlorophyll-a.
- Timing and magnitude of phytoplankton blooms.
- Periods of relatively low and high chlorophyll-a concentrations.

### 3.4 Relationships Between Environmental Variables

- Temporal correspondence between SST and chlorophyll-a.
- Potential seasonal relationships with coastal upwelling.

*Results will be updated after completion of analyses.*

---

## 4. Discussion

*Target: 900 words*

### 4.1 Environmental Drivers of Nearshore Variability

- Influence of seasonal upwelling.
- Localized warming within Monterey Bay.
- Seasonal changes in phytoplankton biomass.

### 4.2 Implications for Juvenile White Shark Thermal Habitat

- Potential availability of thermally suitable habitat.
- Ecological significance of localized warm-water conditions.
- Implications for juvenile white shark range expansion.

### 4.3 Potential Relationships Between Productivity and Habitat

- Chlorophyll-a as an indicator of phytoplankton biomass.
- Potential bottom-up influences on coastal food webs.
- Limitations of interpreting chlorophyll-a as prey availability.

### 4.4 Limitations of Remote Sensing

- Satellite spatial and temporal resolution.
- Cloud blockage and missing observations.
- Surface versus subsurface thermal conditions.
- Limitations of inferring animal habitat selection from environmental
observations alone.

### 4.5 Future Research Applications

- Integration with passive acoustic telemetry.
- Fine-scale vertical temperature measurements.
- Juvenile white shark residency and space use.
- Applications to ongoing graduate thesis research.

---

## 5. Conclusion

*Target: 250 words*

- Summarize the principal environmental patterns.
- Discuss implications for potential JWS habitat.
- Identify opportunities for integrating remote sensing with
acoustic telemetry.

---

## Acknowledgements

Ocean Tracking Network (OTN), Northeastern Pacific Acoustic Telemetry (N-PAcT) network, CSULB Shark Lab, NOAA CCME, Coral Maya Conservation, COAST, Myers Trust.

## Declaration of Competing Interest

TBD.

## Data Availability

Data acquisition notebooks, code, and figures will be
available through this GitHub repository. Original environmental
datasets are publicly accessible available.

---

## References

Ketchum, James & Hearn, Alex & Klimley, A. & Espinoza, Eduardo & Peñaherrera, César & Largier, John. (2014). Seasonal changes in movements and habitat preferences of the scalloped hammerhead shark (Sphyrna lewini) while refuging near an oceanic island. Marine Biology. 161. 10.1007/s00227-013-2375-5. 

Montalto, Kelsey H. (2025). "Juvenile White Sharks in Monterey Bay: Effects of Thermal Habitat Patchiness on Local Densities of a Novel Range Shifting Predator". Capstone Projects and Master's Theses. 2003. https://digitalcommons.csumb.edu/caps_thes_all/2003. 

Ryan, J. P., A. M. Fischer, R. M. Kudela, M. A. McManus, J. S. Myers, J. D. Paduan, C. M. Ruhsam, C. B. Woodson, and Y. Zhang. (2010). Recurrent frontal slicks of a coastal ocean upwelling shadow, J. Geophys. Res., 115, C12070, doi:10.1029/2010JC006398.

Spurgeon, Emily, James M. Anderson, Yi Liu, Vianey Leos Barajas, Christopher G. Lowe. (2022). “Quantifying thermal cues that initiate mass emigrations in juvenile white sharks.” Sci Rep 12: 19874. https://doi.org/10.1038/s41598-022-24377-1. 

Spurgeon, Emily, Marten L. Thompson, Mitchell D. Alexander, James M. Anderson, Patrick T. Rex, Brian Stirling, Kevin Abbott. Christopher G. Lowe. (2024). “The influence of micro-scale thermal habitat on the movements of juvenile white sharks in their Southern California aggregation sites.” Front. Mar. Sci 11: 1290769. https://doi.org/10.3389/fmars.2024.1290769. 

---

## Figures

### Figure 1. Study Area and Spatial Environmental Conditions

Draft map of Monterey Bay showing the geographic study area and
satellite-derived environmental conditions.

### Figure 2. Temporal Environmental Variability

Time series of mean sea surface temperature anomalies and
chlorophyll-a concentrations within the nearshore study area.

### Figure 3. JWS occupancy with Chl-a

Comparing residence of JWS with Chl-a.

### Figure 4. JWS occupancy with SST and SSTA

Analysis of the relationships between JWS residence and SST/SSTA.