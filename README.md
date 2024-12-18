# calibrar14ages_surface_sediments

Goal: Phython code developed calibrated radiocarbon ages in surface marine sediments. The ages can be corrected using regional marine surface reservoir ages expressed as R (R = 14C from the ocean - 14C from the atmosphere), which represents the deviation from the SHCal20 curve at a given time, using the python library iosacal 0.6.0 (Costa et al., 2022, https://pypi.org/project/iosacal/). 
All calibrated ages are reported as years Before Present (BP, considering present the year 1950). We considered foraminifera with radiocarbon ages >1950 (Post-radiocarbon boom period) or samples with radiocarbon ages smaller than the average of the different regional modern reservoir ages calculated for as specific region as recent. 

### Prerequisites
- Text file manager (eg. note ++, Excel).
- Python software https://www.python.org/downloads/ 
- https://jupyter.org/
- calibrar14Cages_surface_sediments.ipynb 

Imputs:
- raw 14C ages with errors
- SHCal20 Southern Hemisphere Calibration, 0–55,000 Years cal BP (Hogg et al., 2020) https://www.cambridge.org/core/journals/radiocarbon/article/shcal20-southern-hemisphere-calibration-055000-years-cal-bp/2C20CF55E1251FD2822B009EB795C080 
- regional marine surface reservoir ages expressed as R 

Necesary libraries to be imported to run the code: 
- pandas 
- numpy
- python library iosacal 0.6.0 (Costa et al., 2022, https://pypi.org/project/iosacal/) 
