# baltimore-ambulance-optimization
Optimized Baltimore ambulance placements using a Mixed Integer Linear Program (MILP) to maximize patient survival rates.  

- Clustered 80,959 historical 911 calls using K-means to generate realistic demand zones and call-volume weights. 

- Integrated clinical survival probability functions directly into the objective and used EMS Unit Hour Utilization constraints to prevent unit overloading.  

- Boosted the expected city-wide survival rate to 60.83% (+1.59% over baseline) with a 25-ambulance fleet.  

- Identified a 45-ambulance saturation point, proving maximum theoretical survival can be achieved with 13 fewer units than the full 58-station network. 
