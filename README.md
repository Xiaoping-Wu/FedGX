# FedGX: Federated GWAS across biobanks

Using available code from FedGen. 
https://github.com/collaborativebioinformatics/FedGen

# Summary

Federated Learning Structure — 3 Sites (HUNT Cloud, Brev)

## Planned Steps

1. Synthetic dataset creation across 3 sites

- DougSpeed.com — check whether the software can control for ethnicity (needs verification)
- Genotype/phenotype mapping

2. Client pipeline for GWAS software

- Extension of REGENIE, towards PLINK, GCTA, SAIGE, and custom approaches
- Small edits to server-side GWAS code
- Possibly LD structure handling

3. Standardization of summary stats

4. Meta-analyses

FFX — currently implemented
RFX — currently buggy

5. Visualisation component (bonus, not core scope)

6. PRS (open question — not yet scoped)

# Plan
  ![Federated GWAS architecture](federation_architecture.png)
 
# Team members
* Allan Lind-Thomsen
* Xiaoping Wu
* Marlene Rietz [writer]
* Moh
* Pravesh Parekh
* with inputs from Anders Dale
