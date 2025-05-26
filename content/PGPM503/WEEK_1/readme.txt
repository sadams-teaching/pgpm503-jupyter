# clopidogrel.tsv

This dataset contains simulated pharmacogenomic response measurements for patients given either clopidogrel or codeine.

Each row is a patient. Columns:

- Patient_ID: A unique identifier
- Gene: The gene relevant to the drug metabolism (e.g. CYP2C19)
- Genotype: Star allele diplotype (e.g. *1/*2)
- Phenotype: Interpreted metabolizer status (e.g. PM = Poor Metabolizer)
- Drug: Clopidogrel
- Response_Measure: A simulated number indicating clinical response (e.g., platelet reactivity)
- Age: Patient age in years
- Sex: M or F