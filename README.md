# slr-surge-analysis

Creating a model for surge extent in the Sacramento-San Joaquin River Delta under different RCP and projection models. 

Key for projection models:

- Projection 01: RCP 4.5, ACCESS
- Projection 02: RCP 4.5, CanESM2
- Projection 03: RCP 4.5, CMCC-CMS
- Projection 04: RCP 4.5, CNRM-CM5
- Projection 05: RCP 4.5, GFDL-CM3
- Projection 06: RCP 4.5, HadGEM2-CC
- Projection 07: RCP 4.5, HadGEM2-ES
- Projection 08: RCP 4.5, MIROC5
- Projection 09: RCP 8.5, ACCESS
- Projection 10: RCP 8.5, CanESM2
- Projection 11: RCP 8.5, CMCC-CMS
- Projection 12: RCP 8.5, CNRM-CM5
- Projection 13: RCP 8.5, GFDL-CM3
- Projection 14: RCP 8.5, HadGEM2-CC
- Projection 15: RCP 8.5, HadGEM2-ES
- Projection 16: RCP 8.5, MIROC5


Constant (from MLR) = 0.008 


Each projection has the following components:

- HTOT is the total water level height including all terms
- HAST is predicted astronomical tide
- HSLR is the SLR scenario
- HMETTOT is the total height due to meteorological/climate influences
- HMETSLP - meteorological component due to local SLP fluctuations
- HMETSST - component due to local SST fluctuations 
- HMETENSO - component due to ENSO
- HMETWIND - component due to local winds