# Group-9-project-2


## **Team Members:**

1. Shritha Gorla [@shrithagorla](https://github.com/shrithagorla)
2. Ella Ransell [@edr82569](https://github.com/edr82569)
3. Logan Dwyer [@logandwyer](https://github.com/logandwyer)
4. Matthew Robertson [@matthewROB](https://github.com/matthewROB)

## Description of Data Set

This data set details the count of deaths by overdose from different drugs. 

The data is organized by the time period in which the deaths occurred, the location in which they occurred, the drug that caused the overdoses, and a count of the deaths that occurred in that time frame, in that location, from that particular drug. 

## Questions

1. How is the Southern US affected by drugs that consistently pass through the southern border?
2. Did the COVID-19 Pandemic result in an increased number of drug overdoses?

## Manipulations
- The original set of data listed the data points by regions 1-10, each region corresponding to several states in the US. In order to create a geographic representation of the data, we made an additional table describing which region corresponds to which states, and joined the table to the data through the variable “Jurisdiction.”
- Time Data: Multiple variables indicate the year and month of which each row of data pertains. Additional variables are included specifying the time frame in which the data was collected. 
- Location Data: The variable “Jurisdiction” describes where the information in a row of data is from. The locations are divided up by 10 regions, as well as the country as a whole. 
- Substance Data: The variable “drug_involved” specifies the drug that row pertains to.
 
## Analysis
- We wanted to create a visual comparison of the number of deaths in each region within the data collection time frame, to see if we could locate any patterns or anomalies in drug-related deaths by location. 
- By comparing the numerical counts of deaths by region visually, we can recognize more easily which geographic areas need more attention or intervention in preventing drug overdose deaths.
- Chart 1:
  - Fentanyl is the primary drug impacting the southern U.S.
  - Its prominence helps explain why it's a major topic among government officials
  - Region 4 (Southeast U.S.) experiences the highest rate of drug-related deaths
  - While the exact cause isn’t clear from the data, Region 4 clearly demands deeper investigation
  - Shows how the inflow of drugs from the southern border is negatively impacting these states.
- Chart 2
  - When looking at the line chart, we can see a significant jump in drug overdose when the pandemic begins. This is most likely due to: Mental Health (Isolation, Job Loss, Lockdowns), Treatment Disruptions, Economic Stress
  - Due to this stress factors, people turned to drugs as an escape from circumstances, resulting in the overdose death tally to go up.
 
## Conclusion
- Our data exploration revealed major trends in U.S. drug use and overdose patterns
- National shutdowns appeared to influence increases in drug-related deaths
- Fentanyl and other synthetic opioids continue to drive the crisis across many regions
- The data makes one thing clear: the U.S. is facing a nationwide drug problem
- It’s crucial that we:
  - Support individuals struggling with addiction
  - Advocate for stronger public health resources
  - Encourage government action through effective legislation
- Addressing this crisis requires collective awareness, compassion, and urgency

