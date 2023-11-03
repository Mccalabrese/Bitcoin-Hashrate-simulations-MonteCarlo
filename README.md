### Project-1-.-

##Fintech Bootcamp Module 8: Project 1

#Project Title: Strategic Location Selection for Bitcoin Mining 

#Team Members:
Stella Dong
Russell Gould
Michael Calabrese
Dina Uddin

#Project Description Outline:
The team is interested in predicting future hash-rates for crypto mining by countries (market dependent).  

#Research Questions to answer:
Which countries have the most significant hash rates (15 largest in the market)?
Predict when the US hash rate for Bitcoin exceeds 50% (currently at 37.84%)?
Predict top 5-10 markets y/y increase (monte carlo simulations)
EXTRA: Energy cost vs. hash rate (plot total cost of crypto mining / vs. cost per unit of energy) 

#Data sets to be used:
https://ccaf.io/cbnsi/cbeci/mining_map

#Data Analysis Flow:
Import APIs/CSV with prior hash rate history by country and market (3 years)
Clean data and createdData frames with rates of change (daily/monthly)
High level statistical summaries with variance / stdev
Plot data to visualize country overlay of hash rates (PyViz)
Perform monte carlo simulations for prediction of future hash rates (initial investments  = energy?)
