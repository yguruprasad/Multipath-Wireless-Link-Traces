This folder contains the trace pairs (wifi and cellular link data at the same time and space) collected at two locations
* Stony Brook University (SBU), New York
* Farmingdale State College (FSC), New York 

where 
* the trace file name format is pathID_trial_network.csv
* each trace file has a CSV format timeInSeconds,BytesPerSecond

## Trace description at SBU
Explanation for pathIDs
* path 7: SBU walk SAC side door to the bus stop (WiFi should get weaker)
* path 8: SBU library walk from Central Reading Room to outside by the side door towards Stellar center (WiFi should get weaker)
* path 11: SBU East side Dining Hall indoor walk from Pizza V. to Tool Rd Deli (WiFi can vary or not)
* path 12: SBU outdoor bench across Psych A bldg to indoors library right outside central reading room (WiFi should get stronger)
* path 13: walk starting at SBU music building outdoor right across the art building to inside the first floor of music building, make right to go down stairs to the basement of music building (cellular should get weaker)

![SBUPathsAnnotated](https://user-images.githubusercontent.com/2316553/211053414-047d7cc5-26df-4487-837f-bc40b30e6904.png)

### Trace visualization and statistics at SBU
![all-paths](https://user-images.githubusercontent.com/36745106/221439427-4bbd00de-e09c-42c4-99bf-fb40ec124bf5.png)

A Python notebook with summary statistics of each trace pair is available at the following link: https://colab.research.google.com/drive/14-OClGxWto5T_hfrjxkzlxvn1PXcTFNL

## Trace description at FSC
Explanation for pathIDs
* path 21: Whitman Hall North-West doors to Gleeson Hall South-West doors (building to building)
* path 22: Whitman Hall North-East wing traversal (building to building)
* path 23: Whitman Hall stairwell from 2nd floor to 1st floor to basement (indoors)

| PathID             |  Path Image |
:-------------------------:|:-------------------------:|
Path 21|![path21_whit_NWdoors_glee_SWdoor](https://github.com/aydini/Multipath-Wireless-Link-Traces/assets/36745106/5afd1d47-3809-4d86-8435-464e345f89c6)
Path 22|![path22_whitNE_wing](https://github.com/aydini/Multipath-Wireless-Link-Traces/assets/36745106/59d08cbc-c2b8-43d5-9ca6-43b10e1124b3)
Path 23|![path23_whit_stair_21B](https://github.com/aydini/Multipath-Wireless-Link-Traces/assets/36745106/879cfe6c-7799-45ff-bd3e-553eaab4f87d)

### Trace visualization and statistics at FSC
![fscSpring2023Traces](https://github.com/aydini/Multipath-Wireless-Link-Traces/assets/36745106/b4284add-6712-4489-8281-07e337025a05)

A Python notebook with summary statistics of each trace pair is available at the following link: https://colab.research.google.com/drive/14-OClGxWto5T_hfrjxkzlxvn1PXcTFNL

