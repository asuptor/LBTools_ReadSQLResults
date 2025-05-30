This Grasshopper script allows reading multiple SQL files from Dragonfly/URBANopt simulations.

It appears that multipliers are NOT required on ‘heating’, ‘cooling’, and ‘hot_water’, 
as the sum of the time-series value are equal to the totals in the EnergyPlus Report tables.

However, ‘lighting’ and ‘electric_equip’ (and possibly other energy services which are not in my simulations) 
do need to be multiplied by the Zone Multiplier in order to match the annual total in the EnergyPlus Report tables.


REQUIREMENTS:
Rhino 8 (due to Python 3 script components)
Ladybug Tools suite of plug-ins
TT Toolbox plug-in
