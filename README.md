# FalloutModel

Being currently on the market to buy a rural house in the vicinity of Montreal, amid all the talk of a possible World War 3, I thought it would be interesting to use some open data on wind speeds and directions to model where the fallout would be likeliest to head, should a nuclear bomb be dropped on my city. The goal, of course, is to make an educated guess as to where it would be safest to shelter if such an event were to happen.

This is still a work in progress. The next steps will be to:  
1. divide the area in a grid and use the available data to interpolate each sub-area's wind speed and direction;
2. build a model that estimates the diffusion of fallout between sub-areas for a given set of conditions;
3. perform a bunch of simulations to produce a probabilistic distribution of diffusion patterns.

Stay tuned!
