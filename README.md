# indianocean_bycatchPSA_ms
code for Roberson et al 2022 (Fish and Fisheries): Spatially explicit risk assessment of marine megafauna vulnerability to Indian Ocean tuna fisheries

###<><>>< 2021 version of effort data:

V1: row identifier
Lat / Lon centroids of 0.5 degree cells 
Gear 
NomActive: nominal effort. Nom effort in days at sea-kW for the active vessels (approx. 70% of vessels are active at any given time)
EffActive: effective effort with Creep (I excluded this for this short time period)
Length_Category: For this new version of the effort, vessel classification line with the FAO classification of vessels, so they are classified by length instead of power.
NV: Number of vessels  
P: engine power (kW)
GT: Gross Tonnage
Year 
Sector: Artisanal powered, Unpowered, Industrial 
NB: NomActiveHours/EffActiveHours:
The effort (per year) in hours (fished hours-kW).
That is up to you what you prefer to use, if you are focusing on the action of fishing itself, then the hours are better, but if you are focusing on the time spend at sea, then the DAS works best.
FGroup: Noted -> Now large pelagics instead of "tuna and tuna likes". Use  "pelagic30-90cm" and "pelagic>=90cm" and remove "pelagic<30cm" to focus on tuna