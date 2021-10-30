# Demand-forecast-Supply-chain-Simulation
Transportation and Supply chain Simulation project - ISyE 6203

The purpose of this project is to develop a better understanding of the dynamics of a supply chain, and especially the dynamics of demand forecast evolution based on multiple vertically and horizontal members on supply chain system. With that, the project also shows the bullwhip effect in a supply chain, and how lead time and the weight forecasts place on the most recent data affect forecast evolution and the bullwhip effect over the long period of time.

Basic Exponential smoothening method towards forecasts were also used here in each case ES1,2,3. 
Ex. ES1 :- each firm collects data of its own customer orders, and each firm uses simple exponential smoothing to forecast mean future demand 
F(t + 1): F(t + 1) := (1 − α)F(t) + αD(t) and O(t) = max {(L + 1)F(t + 1) − IP(t), 0}
