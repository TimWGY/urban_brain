# Urban Brain Project

### Subway

Main Question 1: What determines/influences ridership at each subway station?

Question 1A: Should we analyze different kinds of ridership (i.e. for work, leisure, errands)? While most stations are likely to serve all these different purposes, are there temporal patterns?

Question 1B: Should we identify factors by finding coincidental changes across time or by running regression analysis on a snapshot? What are the metrics to evaluate a good explanation?

Question 1C: Should we distinguish between what "determines" ridership (explains a large proportion of variation, changes slowly over a long term) and what "influences" ridership (explains small fluctuations and short-term trends)? At what temporal scale should we aggregate the data? Annual, monthly, or daily ridership? 

Question 1D: Should we analyze different kinds of card types (regular fare, 30-day pass, ..., which may indicate different user clienteles)?

Question 1E: Should we factor in the competition from other modes of transportation? If so, should we model those networks into the analysis for explaining subway ridership? (There are many people who need to go from Place A to Place B for work, but the subway is the only way to go A-B thus it has large ridership but there may be an alternative transport say bus that also goes A-B so ridership is not as large.)

Question 1F: For features of the station, how to create the catchment area? Using specific entrances or station centroid? Consider all modes (walk, bike, bus) or connection trips? 

Question 1G: For features of the station, what to include? Numbers of residents, jobs, points of interest in the catchment area? Demographics, job types, POI types? Demand O-D pair matrix? Routes and reachable stations (and their features)?

