# 2026-Powdery-Mildew-Spillover

The data and codes available here accompany the paper: Hwang et al. 2026. Spillover of Disease Control Costs Between Fields: A Causal Inference of Interference on a Continuous Disease Transmission Network.

The data files provided include the following variables.

Susceptibility_to_R6_Strains: Each cultivar an ordinal score for its susceptibility to pathogenic races of P. macularis with virulence Vb,V3,V4,V5,V6.

Susceptibility_to_nonR6_Strains: Each cultivar an ordinal score for its non-susceptibility to pathogenic races of P. macularis with virulence Vb,V3,V5.

Initial_Strain: The initial strain of P. macularis detected in each hop yard was determined as being virulent or not on cultivars possessing R6. We coded the initial strain as ‘1’ if the pathogen was non-V6-virulent (ie, race Vb,V3,V5) and ‘2’ if the pathogen was V6-virulent (ie, race Vb,V3,V4,V5,V6). If we could not obtain isolates or virulence data or when powdery mildew did not occur at any level, we coded the initial strain as ‘0’.

Pruning: Thoroughness of spring pruning rated using a 1 to 5 ordinal scale. In this ordinal scale, ‘1’ represents the most thorough pruning which removed all green leaves and stems from every plant. Each subsequent point represents an approximation of the incidence of plants with green foliage remaining such that a ‘5’ indicates that >80% of plants had green leaves and shoots remaining after pruning.

FlagShoot_Incidence: Seasonal mean incidence of bud infection which might cause shoots emerging from winter dormancy colonized by P. macularis.

Monthly degree transmission network 1: Monthly outward degree centrality calculated for monthly time transitions considered wind, area, fungicide uses from month to month for each network of yards planted to cultivars that possess R6.

Monthly degree transmission network 2: Monthly outward degree centrality calculated for monthly time transitions considered wind, area, fungicide uses from month to month for each network of yards planted to cultivars that do not possess R6.

Mildew_Apr: Incidence of plants with powdery mildew in April.

Mildew_May: Incidence of plants with powdery mildew in May.

Mildew_Jun: Incidence of plants with powdery mildew in June.

Mildew_Jul: Incidence of plants with powdery mildew in July.

Monthly ingredients: Monthly number of pesticide active constituents applied by hop yard and year for suppression of powdery mildew.

Monthly costs: Monthly costs of pesticides applied by hop yard and year for suppression of powdery mildew. Costs are expressed in real 2022 dollars per hectare.

Synthetic/Non-synthetic/Mixture (count): A type of fungicide uses
