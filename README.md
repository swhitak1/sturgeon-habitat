# 🐟 Atlantic Sturgeon Habitat Suitability Modeling in the Chesapeake Bay

### 📍 Project Overview
This project models seasonal habitat suitability for **Atlantic sturgeon (Acipenser oxyrinchus)** across Chesapeake Bay tributaries using multivariate water quality data and geospatial analysis. The study integrates logistic regression modeling in R with hydrologically corrected spatial processing in QGIS to identify critical habitats for this federally endangered species.

### 🔬 Research Significance
Atlantic sturgeon are a keystone, anadromous species whose recovery is directly linked to riverine habitat quality. Identifying environmental thresholds and spatial patterns of suitability informs ongoing conservation and restoration efforts in the Chesapeake watershed.  

### 🧪 Methodology
- **Data Sources:** USGS National Water Information System (NWIS), NOAA Chesapeake Bay Environmental Data  
- **Variables:** Temperature, dissolved oxygen, pH, turbidity, nitrate, conductance, and discharge  
- **Analysis:**  
  - Binary habitat classification based on published ecological thresholds  
  - Logistic regression (full, reduced, and regularized models) with ROC/AUC evaluation  
  - Seasonal predictions rasterized in QGIS with GRASS GIS hydrological correction  

### 🌊 Key Outputs
- Seasonal habitat suitability maps across major tributaries  
- ROC and AUC performance comparisons of multiple models  
- Variable importance analysis for environmental predictors  
- A reproducible workflow combining statistical modeling with GIS visualization  

### 📎 Tools & Techniques
- **R:** glm, caret, glmnet, pROC  
- **GIS:** QGIS, GRASS GIS, ArcGIS Pro for cartographic refinement  
- **Visualization:** Seasonal raster maps, ROC curves, and environmental response plots

### 📖 Links

### 📄 Project Files
- 📕 [Full Manuscript](./SWhitaker_Full_Manuscript.pdf) – Complete research paper with methodology, analysis, and conservation implications.
- 🖥️ [Presentation](./Sturgeon_Presentation.pdf) – Condensed visual summary of methods, results, and key findings.
- 🗺️ [Seasonal Habitat Maps](./seasonal_maps.gif) – Animated visualization of predicted habitat suitability across seasons.
