# DER-Hosting-Capacity-Analysis
This is my first repositry representing the Analysis of Low Voltage Distribution System with the penetration of PV generation.

The analysis is carried out in OpenDSS with VBA-COM interface by using real low voltage network IEEE European Low Voltage feeder. The results display the voltage variation at feeder head and feeder end as well.

Voltages at each load point is also modelled to understand the behaviour of network under DER and No-DER conditions.

**How to Run**
1. After downloading the files copy into the directory specified with no space (e.g. F:\DER_Analysis )
2. Change the main path in excel file with your specified directory in cell 'D3'
3. PV penetration level specifies the PV equiped at each load "1" and No PV with "0"
4. 24 hour simulation is carried out with 5-min resolution
