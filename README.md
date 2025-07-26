## Category: 
Graph-based Decision Trees with Feature Engineering
## Method: 
Spatiotemporal Graph Construction, eXtreme Gradient Boosting (XGBoost), Feature Engineering, Clustering, Spatial Vector Autoregressive Lasso (SVARL)
## Topic: 
Ridership Forecasting for Docked Bike-Sharing Systems and Relationship with Public Transit and Urban Streets
## Research Design: 
It remains unclear whether there are any potential changes in ridership prediction accuracy by integrating various feature groups, as well as the extent of such changes. Particularly, there is a dearth of understanding of the effects of public transit variables and street characteristics on bike-sharing ridership patterns and forecasts. To address this gap, we put forward a novel feature engineering approach that explicitly integrates spatiotemporal characteristics of bike-sharing trips and their influencing factors into an explainable machine learning model, XGBoost, for analyzing and predicting ridership patterns. Using XGBoost as a backbone, this research aims to uncover the effects of different influencing factors on prediction accuracy and reveal the relationships between bike-sharing ridership and public transit systems (e.g., transit networks and schedules) and street characteristics from street view imagery. These insights offer actionable guidance for optimizing bike-sharing system design and improving the plans of transit networks and schedules to promote bike usage and multimodal integration in urban transport. Finally, we demonstrate the explainable machine learning-based feature engineering approach by applying 2019 trip data from the Capital Bikeshare Program in Washington, D.C., to the research design outlined in Figure bolow.

<table style="margin-left: auto; margin-right: auto;">
  <tr style="text-align: center;">
    <td><img src="Figures/Research Flowchat-new.png"></td>
  </tr>
 </table>

## Key Findings: 
Spatiotemporal graph-based decision tree models were developed to predict short-term ridership trends and assess the influence of transit access and street features. These models outperformed benchmarks across various datasets (e.g., all-hour, non-zero, and rush-hour subsets) and spatial units (e.g., individual stations, proximity-based groups, and usage-based clusters). Incorporating transit and urban street features significantly improved predictive accuracy, especially in high-demand areas and during rush hours. Stations within 100 meters of bus stops and 50 meters of metro stations, or near transit hubs and open, active street environments, consistently saw higher ridership. These results derived from this AI-augmented transport planning framework underscore the importance of integrating transit accessibility and urban form into micromobility planning for better multimodal coordination.
## Paper available at https://doi.org/10.1016/j.jtrangeo.2025.104356
