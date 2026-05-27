#### Absorption and formulations

The model includes oral solution, capsule-as-solution and tablet applications. Solution and capsule-as-solution scenarios were used to separate systemic disposition from dissolution-limited tablet absorption. Tablet absorption was described with formulation-specific dissolution and particle-size assumptions, with fed-state scenarios used to describe the reduced and delayed absorption observed for weak-base ketoconazole under altered gastrointestinal conditions [Marok 2023](#5-references), Table 1.

#### Distribution

Ketoconazole is a weak base with high plasma protein binding and pH-dependent solubility. Distribution parameters were based on physicochemical properties and PBPK tissue partitioning methods, with optimized lipophilicity where required to reproduce systemic exposure. The metabolites were represented as separate compounds with their own physicochemical properties and protein-binding assumptions [Marok 2023](#5-references), Table 1.

#### Metabolism, transport and inhibition

Ketoconazole metabolism includes formation of N-deacetylketoconazole by arylacetamide deacetylase and further metabolism through CYP3A4 and UGT pathways. Ketoconazole and metabolites were represented as CYP3A4 and P-gp inhibitors, which is required to describe the observed DDI perpetrator behavior more accurately than a parent-only inhibition model [Marok 2023](#5-references), Table 1, and [Weiss 2022](#5-references).

#### Automated parameter identification

Parameters that could not be fixed from independent physicochemical or in vitro evidence were optimized against the clinical plasma concentration-time profiles. Optimized parameters include formulation-related dissolution terms and selected compound-specific disposition parameters. Kinetic symbols are reported in the generated input tables with the corresponding source metadata from the model.
