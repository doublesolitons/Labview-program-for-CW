# Labview-program-for-CW
-----------------
COPYRIGHT to Biomedical Optical Technologies Lab @ Boston University. Developed by FEI TENG
-----------------

This includes programs for testing Gen2 and Gen3 system under several testing conditions

Part 1:
Test Gen2 system with benchtop instruments

Hardware requirement
1: NI DAQ USB 6361
2: Current controller LDX-3525B
3: Customized analog bandpass filter (1KHz central frequency)
4: Gen2 wearable probe
5: HDMI cable

Software requirement
LabView 2016

Input to the LabView program
1: DC current
2: Modulation depth
3: # of warm-up measurement
4: # of data-collecting measurement
5: Acquisition speed
6: Measurement name
7: Bandpass filter settling time (in ms)
8: Underlying tissue type
9: Channel selection for read-time demonstration of hemodynamics

Output from LabView program
1: Voltage data from optical transducers for each measurement channel
2: Real-time demonstration of tissue hemodynamics for selected channels
3: Measurement summary


Part 2:
Test Gen2 system with portable instruments

Similar to Part 1, except the following items

Hardware requirement
1: NI DAQ OEM 6361
2: Current controller FL591FL


Part 3:
Test Gen3 system with portable instruments

















 