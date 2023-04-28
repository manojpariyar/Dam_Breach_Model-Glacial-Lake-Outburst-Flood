# Scenario-based Modelling of Glacial Lake Outburst Floods and their impact assessment downstream

This study aims to conduct 2D dam-breach modelling in HEC RAS of a potentially dangerous glacial lake at Jostedalsbreen, Norway to assess potential impact downstream in case of outburst, basically focussing on the number of buildings and the river sections flooded above 2 meter water depth. The three different scenarios are Optimistic, Intermediate and Pessimistic which are assumed based on the three different conditions differing the volume of drained water at the lake,  flood hydrograph (flood duration, peak discharge, peak discharge time), and manning's roughness coefficient. The scenario parameters are as follows:

![image](https://user-images.githubusercontent.com/114010808/235078435-ad87c6f7-62c0-4eca-adbd-94d938825b7c.png)

Due to lack of actual data, flood hydrographs for three different scenarios are assumed as follows. 

![image](https://user-images.githubusercontent.com/114010808/235077268-8f8b8db8-8371-41e7-9a6d-01341505ec20.png)

The surface area of lake is obtained from digitizing the Sentinel 2 imagery. Mean depth, total volume and peak discharge are obtained from derivative equations (Empirical formula) as mentioned below:

Dm = 3 * 10-5 A + 12.64 ………… equation 1

V = A * Dm ……………. equation 2

Qmax = 0.72 V0.53 ……………… equation 3

Here, A is lake surface area, Dm is mean water depth of lake, V is volume of lake water, and Qmax is peak discharge of lake water.

## References:
Kougkoulos, I., Cook, S. J., Edwards, L. A., Clarke, L. J., Symeonakis, E., Dortch, J. M., & Nesbitt, K. (2018). Modelling glacial lake outburst flood impacts in the Bolivian Andes. Natural Hazards, 94(3), 1415–1438. https://doi.org/10.1007/s11069-018-3486-6
