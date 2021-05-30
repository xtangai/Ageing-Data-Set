*******************************************************************
This folder contains the Data and Code related to 'Recovering large-scale battery ageing data-set with machine learning'.
Overall 9 files should be downloaded.
*******************************************************************
Please use 'Missingdatarecovery_main.m' to generate Fig. 1
Please use 'Capacityestimation_main.m' to generate Fig. S14

You may use 'Differentlabelplacement_main.m' to generate results with different placements of the labels.
By changing
	Tps = [0.01,0.5,1];
into different values (0%~100%) to generate different results, for instance:
	Tps = [0.1,0.25, 0.7, 1];
you change the positions of the labels from (1%, 50%, and 100%) into (10%, 25%, 70%, and 100%).
Both the positions and the numbers of the labels could be changed.


*******************************************************************
We have overall 18 datasets, please refer to Table S1.
Each data set (e.g., ME2600_T3 or SY2150_ACC) contains 18 domains:

cyc          -- cycle number
Ccap       -- Capacity obtained from constant-current-constant-voltage charging
Dcap       -- Capacity obtained from constant voltage discharging

CCCHGV -- Voltage of constant current charging
CCCHGI  -- Current of constant current charging
CCCHGC -- Capacity of constant current charging

CVCHGV -- Voltage of constant voltage charging
CVCHGI  -- Current of constant voltage charging
CVCHGC -- Capacity of constant voltage charging

CCDCHV -- Voltage of constant current discharging
CCDCHI  -- Current of constant current discharging
CCDCHC -- Capacity of constant current discharging

DWTV -- Voltage of waiting after discharging
DWTI  -- Current of waiting after discharging
DWTC -- Capacity of waiting after discharging

CWTV -- Voltage of waiting after charging
CWTI  -- Current of waiting after charging
CWTC -- Capacity of waiting after charging

*******************************************************************
The code was tested with Matlab 2015b.
You may need to run into different results when test the code for multiple times, as the networks are randomly initialised.

**Please contact Dr. Kailong Liu <kliu02@qub.ac.uk> if you have any questions / bug reports**
**Please contact Dr. Xiaopeng Tang <xtangai@connect.ust.hk> if you have any questions / bug reports**
