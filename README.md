# bacterial_plant_fungal_domain_analyzer
This repository contains a datascience based faster implementation of the domain predictions from the interpro scan and it will give you a complete domains information, coordinates and other associative information. I used a mapping dataframe approach to make it faster rather than looping it over and over. 
```python
bacterialProteomeDomainAnalyzer("/Users/gauravsablok/Desktop/CodeTest/json_parser/ipr_scan.json", \
                                                     arg_type = "getdomains")
[['G3DSA:3.30.70.20'],
 ['SSF53323', 'Pyruvate-ferredoxin oxidoreductase, PFOR, domain III'],
 ['G3DSA:3.40.50.920'],
 ['cd07034', 'TPP_PYR_PFOR_IOR-alpha_like', 'TPP_PYR_PFOR_IOR-alpha_like'],
 ['PIRSR005784-1', 'PIRSR005784-1'],
 ['PF01855',
  'POR_N',
  'Pyruvate flavodoxin/ferredoxin oxidoreductase, thiamine diP-bdg'],
 ['G3DSA:3.40.50.970:FF:000012',
  'Pyruvate:ferredoxin (Flavodoxin) oxidoreductase']]
help(bacterialProteomeDomainAnalyzer) # for more information
```
Gaurav Sablok \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany
