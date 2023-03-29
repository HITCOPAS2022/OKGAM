# Regression Kriging with GAM
This workflow consists in creating equispaced gridded data layers by interpolating discrete CTD measurements of oceanographic variables such as temperature, salinity, oxygen and density. This was done with the regression-kriging spatial prediction technique, combining kriging with generalized additive model (GAM) available as libraries in R, developed by Pebesma, E. 2004 and Simon Wood (see Wood, S.N. 2017), respectively. As an example, in situ temperature at 10 m depth was used for each of the profiles collected during the "MOBIO-MPH 2020" cruise, conducted by the Instituto de Fomento Pesquero (IFOP) between September and October 2020 on board the vessel Abate Molina. 

This is part of the research project "Coupling oceanographic and habitat models to assess abundance, distribution, and risk for baleen whales in Chile: Developing new tools for management” undertaken by researchers from Centro de Investigación Oceanográfica en el Pacífico Sur Oriental (COPAS Coastal), Universidad Austral de Chile, Universidad de Valparaíso, Universidad de Concepción, Instituto de Fomento Pesquero (IFOP), Centro de Estudios Avanzados en Zonas Áridas (CEAZA), Oregon State University, and Instituto Aqualie. Funded by COPAS Coastal HIT projects 2022.

![temperature_10m_MOBIO2020](https://user-images.githubusercontent.com/112881671/228532811-ccb29725-7f41-4787-a1e5-093cd898f699.png)
