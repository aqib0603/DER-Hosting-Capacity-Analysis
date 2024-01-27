# DER-Hosting-Capacity-Analysis
This is my first repositry representing and developing an understanding of the Low Voltage Distribution System Analysis with the penetration of PV generation.

The analysis is conducted in OpenDSS with a VBA-COM interface using a real low-voltage network, the IEEE European Low-Voltage feeder. Detailed time-series simulations are displayed to properly assess the technical impacts of DERs (PV Generation) at the feeder head and feeder end.

At each load point, voltage is modelled to understand the network behaviour under DER and No-DER conditions.

**How to Run**
1. After downloading the files, copy them into the directory specified with no space (e.g. F:\DER_Analysis )
2. Change the main path in the Excel file with your specified directory in cell 'D3.'
3. PV penetration level specifies the PV equipped at each load "1" and No PV with "0"
4. 24-hour simulation is carried out with a 5-min resolution
