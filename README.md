# FedGX: Federated GWAS across biobanks

# Summary

At the Nordic Biobank Hackathon, we aim to develop software for federated GWAS across three sites. 
For development, we test this approach in the HUNT Cloud and across two BREV sites. 

We will extend currently available code from the FedGen repository. 
https://github.com/collaborativebioinformatics/FedGen

____________________________

## Planned Steps

1. Synthetic dataset creation across 3 sites

- DougSpeed.com — check whether the software can control for ethnicity (needs verification)
- Genotype/phenotype mapping

2. Client pipeline for GWAS software in *Site 1, 2, 3*

- Extension of REGENIE, towards PLINK, GCTA, SAIGE, and custom approaches
- Small edits to server-side GWAS code
- Possibly LD structure handling

3. Standardization of summary stats in *Central Analytical Engine*

4. Meta-analyses in *Central Analytical Engine*

- FFX — currently implemented
- RFX — currently buggy

5. Visualisation component (bonus, not core scope)

6. PRS (open question — not yet scoped)

____________________________

# Plan
  ![Federated GWAS architecture](federation_architecture.png)
____________________________
 
# Team members
* Allan Lind-Thomsen
* Xiaoping Wu
* Marlene Rietz [writer]
* Moh
* Pravesh Parekh
* with inputs from Anders Dale
