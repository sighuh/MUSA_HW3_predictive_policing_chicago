This is a homework assignment for MUSA Public Policy Analytics at UPenn. 

This project critically examines the use of predictive policing models, using Chicago as a case study. Predictive policing aims to allocate police resources by forecasting crime locations, perpetrators, and outcomes. However, these methods are highly controversial due to inherent biases, particularly in data selection and enforcement practices, which can exacerbate inequities in policing.

The analysis focuses on developing a risk model for predicting criminal damage to vehicles in Chicago. The study incorporates spatial data, census data, and the Chicago Police Department's data. It also addresses the limitations and biases of such models and evaluates the theoretical underpinnings, such as the problematic "Broken Windows Theory," which often criminalizes poverty.

Key Components:

-Data Visualization

Point Data Mapping: Highlights high-density areas of vehicle damage, including neighborhoods like Lake View, Logan Square, and the West Side.
Fishnet Grid: Aggregates crime data into 500x500 ft grids to better visualize risk distribution across the city.

-Feature Engineering

Examines spatial features such as playgrounds, grocery stores, graffiti, abandoned cars, and liquor stores.
Incorporates nearest neighbor metrics to understand spatial risk factors and their clustering.

-Spatial Analysis

Local Moran’s I: Tests for spatial autocorrelation, revealing statistically significant hotspots near the Loop, West Side, and Hyde Park.
Distance to Hotspots: Assesses proximity of grid cells to crime clusters.

-Modeling

Cross-validated Poisson regression models (with and without spatial features) to predict criminal damage.
Comparison of Kernel Density and risk prediction models for temporal generalizability.

-Results
Models including spatial features outperform those without but still show high prediction error.
The model tends to overpredict in majority White neighborhoods and underpredict in majority Non-White neighborhoods, reflecting systemic biases in data and enforcement.

-Findings
Predictive policing models reinforce historical biases and inequities, especially in racially segregated urban areas like Chicago.
These models create feedback loops where past data perpetuate discriminatory practices, further embedding inequities.

-Conclusion
The project concludes that predictive policing models should not be implemented by public or private entities. Instead, efforts should focus on algorithmic justice and ethical applications of predictive modeling, such as in climate risk or fire prediction. By critically examining the limitations of these technologies, the study highlights the risks of relying on biased data and underscores the need for human-centered approaches to societal challenges.
