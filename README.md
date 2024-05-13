
# Resilience Analysis of Traffic Infrastructure using Loss of Serviceability Index

##### - This paper discusses a novel method to evaluate how well traffic infrastructure can handle disruptions, like floods, by looking at the loss of serviceability. They applied this method to a case study in Trier, Germany, finding that the Kaiser-Wilhelm Brücke bridge was the most critical area affected by flooding.

##### - The paper introduces a methodology using Loss of Serviceability (LoS) to assess traffic infrastructure resilience during disruptive events, demonstrated in a flooded area in Trier, Germany.


##### - Insights from the analysis can guide policymakers to enhance transportation system reliability and robustness in similar contexts.

##### - Resilience of traffic systems is achieved through defining resilience, formulating resilience measures, and analyzing resilience measures to understand system robustness.

##### - The case study demonstrates the LoS index methodology using OpenStreetMap and OSMnx to calculate LoS index for flooded areas in Trier and identify critical edges.

##### - Quantitative measures like probability of susceptibility, economic costs, recovery time, and disruption levels are used to measure transportation infrastructure resilience.

##### - The Loss of Serviceability index is utilized to calculate network resilience by considering affected and non-affected areas, identifying critical edges in the network.

##### - For applying our method we choose Tries as a case study. We extracted road networks from Trier main city, nearby Mossel river. Which are more prone to affected by the natural disestar.

## We have extracted road network using OSMnx Library in python

![extracted_area](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/acb592a2-389c-4ebe-9b79-017fd696b2a4)

## Selected Area for case study (Trier Germany)

![selected_area](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/cc76b36b-8283-42e0-9506-153efb77a6e5)

## For reducing time complexity, we have selected some important source and destination point (e.g - hospital, fire station, school) to calculate the LoS value

![source_destination](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/c4754cdb-85a8-4925-bff2-6bb777c96254)



## Final result after applying our methodology (In python dataframe)

![dataframe](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/4dbeee32-bb4b-406e-ba5d-a32a326a7d2d)

## Most Affected paths (based on LoS methodology)

![affected_1](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/2e262be6-0749-45b2-8314-b7d812f66cbf)

## Least Affected paths (based on LoS methodology)

![affected_1](https://github.com/monochandan/Research-Case-Study-2022-University-of-Trier-/assets/29684226/420387dc-4d09-40ac-88ed-d362a3da0bce)


## The completed version of this work was presented at the 9th International Conference on Dynamics in Logistics (LDIC 2024), in Bremen, Germany.
https://link.springer.com/chapter/10.1007/978-3-031-56826-8_10






