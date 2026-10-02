---
layout: default
title: About
---

# About 

**1. Why understanding drought dynamics matters now** 
*Drought in a changing climate* 

Climate change is altering precipitation patterns and reshaping drought dynamics in many regions worldwide.

Longer dry periods and disruptions in water availability can have far-reaching consequences for water resources, agriculture, ecosystems and society. 

Understanding how drought evolves across space and time is therefore increasingly important for improving its characterisation and risk assessment, strengthening preparedness for severe drought conditions, and supporting informed decision-making.

**2. Knowledge gaps (ou Open scientific questions?  the research challenge?)**
**Integrating complementary drought information for spatial assessment and anticipation**

Despite the growing availability of drought monitoring, mapping and forecasting products, important challenges remain in integrating complementary information across spatial and temporal scales.

Drought is a complex and multidimensional phenomenon. 

No single indicator captures every relevant dimension of drought. Its characterisation therefore requires more than a single measure of rainfall: the persistence of dry periods, the frequency of low-precipitation conditions, their severity and spatial variability provide complementary information.

Integrating these dimensions remains challenging, particularly at local scales, where observational information may be spatially uneven, drought behaviour can vary substantially across space and time, and predictive skill may vary across regions, seasons and forecasting horizons.

A further challenge is to translate this integrated information into locally relevant and actionable knowledge that can support preparedness, early warning and informed decision-making.

**3. Our approach (ou What can we do about it?)**
**Integrating spatio-temporal drought characterisation, risk mapping and anticipation**

Our approach uses Spatial Data Science as an integrative framework encompassing spatial and spatio-temporal analysis, geostatistical modelling and data-driven methods to investigate drought dynamics, integrate complementary indicators, represent spatial variability and uncertainty, risk and assess short-term predictive performance.

**Questions guiding our research**
i) What spatial and temporal changes in drought severity and variability can be identified from long-term observations?
ii) What additional information is gained by integrating complementary drought indicators rather than analysing them separately?
iii) Where are the most critical drought-prone areas, how do they evolve over time, and how can their spatial uncertainty be represented?
iv) How accurately can short-term drought severity be anticipated from recent and historical information, and under which conditions does predictive skill decrease?

**Methods at a glance**
i) Drought indicators: our current research uses precipitation-based indicators to describe complementary dimensions of meteorological drought. Consecutive Dry Days (CDD) characterises the persistence of dry spells, while RL10 represents the frequency of days with low precipitation. A Joint Drought Index (JDI) integrates information from both indicators. 
ii) Spatial modelling: Geostatistical methods are used to transform observations recorded at meteorological stations into continuous spatial representations of drought-related variables. Variogram modelling and Direct Sequential Simulation are used to characterise spatial patterns and generate multiple possible spatial realisations, allowing spatial variability and uncertainty to be represented. 
iii) Integrated drought assessment: Multidimensional Scaling (MDS) is used to combine complementary drought information into a Joint Drought Index, allowing the joint spatial and temporal behaviour of the indicators to be analysed and mapped. 
iv) Drought risk mapping: Spatial simulations are used to classify drought severity and identify areas where critical thresholds are more likely to be exceeded. Drought-risk classifications and exceedance-probability maps provide spatially explicit information on critical areas and changes in drought conditions over time. 
v) Drought prediction: Machine-learning methods are used to investigate short-term drought-severity prediction. A Random Forest model has been developed using recent drought conditions together with historical information for the target period. Model performance is assessed using held-out test data and predictive-performance metrics including MAE, RMSE and NSE.

As the research develops, this framework can be extended through additional drought indicators, climatic variables and modelling approaches, while exploring their value for increasingly actionable drought anticipation and early-warning applications.
