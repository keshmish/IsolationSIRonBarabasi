# IsolationSIRonBarabasi
Code for the paper "Quality Criteria for Control of epidemics" by Vikenty Mikheev, 2020. Barabasi temporal graph with SIR model is used to find the optimal delay for an isolation to control the epidemic in a view of two quality criteria: total number of infected and maximum number of infected. The simulations for COVID-19 are run on 5,000 and 10,000 nodes for 180-300 days.

To adjust the code for another SIR-type of infection, change parameters:
p - probability of transfering the infection across one edge in a day
m - parameter of connectedness of Barabasi model, which defines the number of connectons of an induvidual in the society for potential infection transmissions.
LenSick - the length of the time interval when an infected person is contegeous 
groupsize - "no gathering of __groupsize__ and more people"  
