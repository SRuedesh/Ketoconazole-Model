### In vitro and physicochemical data

Table 1 gives the drug-dependent parameters used in the final model. Values were checked against the model snapshot, Table 1, and Supplement Table S1.3 of [Marok 2023](#5). Approved corrections are documented in the table notes. Optimized values are identified as such. Assumed values are traced to the basis stated in the supplement.

| Parameter | Unit | Value | Source | Description |
| --- | --- | ---: | --- | --- |
| **Ketoconazole** |  |  |  |  |
| MW | g/mol | 531.43 | [Chemicalize 2021](#5) | Molecular weight. |
| logP | - | 2.52 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 1 | [Heel 1982](#5) | Fraction unbound in plasma. |
| pK<sub>a</sub>,base | - | 2.94 | [Chemicalize 2021](#5) | pKa of a basic ionization site. |
| pK<sub>a</sub>,base | - | 6.51 | [Chemicalize 2021](#5) | pKa of a basic ionization site. |
| Solubility | mg/L | 2.033 × 10<sup>4</sup> (pH 1.2); 4.3 × 10<sup>2</sup> (pH 3); 1.0 × 10<sup>2</sup> (pH 5); 7.00 (pH 6.8); 6.00 (pH 7.5); 5.40 (deionized water)<sup>c</sup> | [Ghazal 2015](#5), Table 1 | Aqueous solubility in the specified media. |
| Density | g/cm<sup>3</sup> | 1.40 | [ChemSpider 2021](#5) | Solid-state density. |
| D<sub>aq</sub> | dm<sup>2</sup>/min | 3.75 × 10<sup>−7</sup> | Optimized | Aqueous diffusion coefficient. |
| P<sub>int</sub>, fasted | cm/min | 1.56 × 10<sup>−5</sup> | Optimized | Specific transcellular intestinal permeability in the fasted state. |
| P<sub>int</sub>, fed | cm/min | 9.95 × 10<sup>−6</sup> | Optimized | Specific transcellular intestinal permeability in the fed state. |
| GET, fasted | min | 15 | [OSP Suite Manual 2018](#5) | Gastric emptying time in the fasted state. |
| GET, fed | min | 45 | [Fisher 1987](#5) | Gastric emptying time in the fed state. |
| Cellular permeabilities | - | PK-Sim Standard | [OSP Suite Manual 2018](#5) | Cellular permeabilities calculated with the PK-Sim Standard method. |
| Partition coefficients | - | Berezhkovskiy | [Berezhkovskiy 2004](#5) | Tissue-to-plasma partition coefficients calculated with the Berezhkovskiy method. |
| GFR fraction | - | 1 | Assumed | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1 | Assumed | Fraction released continuously into bile. |
| K<sub>m,AADAC</sub> | µmol/L | 1.88 | [Fukami 2016](#5) | Michaelis constant for AADAC-mediated hydrolysis. |
| k<sub>cat,AADAC</sub> | min<sup>−1</sup> | 0.87 | Optimized | Catalytic rate constant for AADAC-mediated hydrolysis. |
| K<sub>m,CYP3A4</sub> | µmol/L | 0.00846 | [Weiss 2022](#5) | Michaelis constant for CYP3A4 metabolism, assumed equal to K<sub>i,CYP3A4</sub>. |
| k<sub>cat,CYP3A4</sub> | min<sup>−1</sup> | 0.10 | Optimized | Catalytic rate constant for CYP3A4-mediated metabolism. |
| K<sub>m,UGT1A4</sub> | µmol/L | 7 | [Bourcier 2010](#5) | Michaelis constant for UGT1A4-mediated glucuronidation. |
| k<sub>cat,UGT1A4</sub> | min<sup>−1</sup> | 0.31 | Optimized | Catalytic rate constant for UGT1A4-mediated glucuronidation. |
| K<sub>m,P-gp</sub> | µmol/L | 0.035 | [Weiss 2022](#5) | Michaelis constant for P-glycoprotein transport, assumed equal to K<sub>i,P-gp</sub>. |
| k<sub>cat,P-gp</sub> | min<sup>−1</sup> | 0.33 | Optimized | Catalytic rate constant for P-glycoprotein transport. |
| K<sub>i,CYP3A4</sub> | µmol/L | 0.00846 | [Weiss 2022](#5) | Inhibition constant for CYP3A4, derived from IC<sub>50</sub>. |
| K<sub>i,P-gp</sub> | µmol/L | 0.035 | [Weiss 2022](#5) | Inhibition constant for P-gp. |
| Particle radius | µm | 11.749; 111.06; 205.46<sup>d</sup> | [Elder 2007](#5) | Particle radii assigned to the specified dose fractions. |
| **N-deacetylketoconazole** |  |  |  |  |
| MW | g/mol | 489.40 | [Chemicalize 2021b](#5) | Molecular weight. |
| logP | - | 3.75 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 1 | [Heel 1982](#5) | Fraction unbound in plasma. |
| pK<sub>a</sub>,base | - | 0.20 | [Chemicalize 2021b](#5) | pKa of a basic ionization site. |
| pK<sub>a</sub>,base | - | 6.42 | [Chemicalize 2021b](#5) | pKa of a basic ionization site. |
| pK<sub>a</sub>,base | - | 8.90 | [Chemicalize 2021b](#5) | pKa of a basic ionization site. |
| Solubility | mg/L | 1.24 × 10<sup>3</sup> | [Chemicalize 2021b](#5) | Aqueous solubility at pH 6.5. |
| Cellular permeabilities | - | Charge-dependent Schmitt | [Kawai 1994](#5) | Cellular permeabilities calculated with the charge-dependent Schmitt method. |
| Partition coefficients | - | Rodgers and Rowland | [Rodgers 2006](#5) | Tissue-to-plasma partition coefficients calculated with the Rodgers and Rowland method. |
| GFR fraction | - | 1 | Assumed | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1 | Assumed | Fraction released continuously into bile. |
| K<sub>m,FMO3</sub> | µmol/L | 1.17 | [Rodriguez 1997](#5) | Michaelis constant for FMO3-mediated N-oxidation. |
| k<sub>cat,FMO3</sub> | min<sup>−1</sup> | 378.65 | Optimized | Catalytic rate constant for FMO3-mediated N-oxidation. |
| K<sub>i,CYP3A4</sub> | µmol/L | 0.022 | [Weiss 2022](#5) | Inhibition constant for CYP3A4, derived from IC<sub>50</sub>. |
| K<sub>i,P-gp</sub> | µmol/L | 0.119 | [Weiss 2022](#5) | Inhibition constant for P-gp. |
| **N-deacetyl-N-hydroxyketoconazole** |  |  |  |  |
| MW | g/mol | 505.40 | [Chemicalize 2022](#5) | Molecular weight. |
| logP | - | 4.20 | [Chemicalize 2022](#5) | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 1 | [Heel 1982](#5) | Fraction unbound in plasma. |
| pK<sub>a</sub>,base | - | 3.42 | [Chemicalize 2022](#5) | pKa of a basic ionization site. |
| pK<sub>a</sub>,base | - | 6.42 | [Chemicalize 2022](#5) | pKa of a basic ionization site. |
| Solubility | mg/L | 4.40 × 10<sup>3</sup><sup>e</sup> | [Marok 2023](#5), Table 1 | Aqueous solubility at pH 6.5. |
| P<sub>organ</sub> | cm/min | 0 | Assumed | Specific organ permeability. |
| Cellular permeabilities | - | Charge-dependent Schmitt | [Kawai 1994](#5) | Cellular permeabilities calculated with the charge-dependent Schmitt method. |
| Partition coefficients | - | Berezhkovskiy | [Berezhkovskiy 2004](#5) | Tissue-to-plasma partition coefficients calculated with the Berezhkovskiy method. |
| GFR fraction | - | 1 | Assumed | Fraction used to scale passive glomerular filtration. |
| EHC fraction | - | 1 | Assumed | Fraction released continuously into bile. |
| CL<sub>FMO3</sub> | L/(µmol·min) | 0.09 | Optimized | FMO3-mediated clearance. |
| K<sub>i,CYP3A4</sub> | µmol/L | 0.022 | [Weiss 2022](#5) | Inhibition constant for CYP3A4, assumed equal to the N-deacetylketoconazole value. |
| K<sub>i,P-gp</sub> | µmol/L | 0.119 | [Weiss 2022](#5) | Inhibition constant for P-gp. |

**Table 1:**<a name="table-1"></a> Drug-dependent parameters used in the final ketoconazole model. AADAC: arylacetamide deacetylase. FMO3: flavin-containing monooxygenase 3. GFR: glomerular filtration rate. P-gp: P-glycoprotein. UGT1A4: uridine diphosphate glucuronosyltransferase 1A4. <sup>c</sup> Parent ketoconazole values were converted from mg/mL in Table 1 of [Ghazal 2015](#5) to mg/L. Table 1 of [Marok 2023](#5) gives an incorrect pH 3 value and assigns pH 7 to the deionized-water value. <sup>d</sup> Supplement Table S1.3 incorrectly labels the particle radii as nm. The snapshot values are equivalent to the listed µm values. <sup>e</sup> The value is 4.40 × 10<sup>3</sup> mg/L, equivalent to 4.40 mg/mL, as reported in Table 1 of [Marok 2023](#5). Supplement Table S1.3 is incorrect.

### Clinical data

Clinical plasma concentration-time profiles were taken from the published studies compiled for the model publication ([Marok 2023](#5)). The evaluation includes 53 oral profiles across solution, tablet, capsule, fasted, fed, single-dose, and multiple-dose conditions ([Table 2](#table-2)). Seven profiles were used for model building, and 46 profiles were used for model verification. When a source publication also describes an interaction study, this compound report includes only ketoconazole or metabolite pharmacokinetics and does not evaluate victim-drug exposure.

| Source | Dose [mg] / schedule\* | Age [years] | Weight [kg] | Sex | N | Form. | CYP2D6 characterization |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| [Boyce 2012](#5) | 200, multiple dose, profile 1, fasted | 26.6 (18–39) | 73.5 (53.8–98.8) | 41.67% female | 24 | Tablet | EM |
| [Boyce 2012](#5) | 200, multiple dose, profile 2, fasted | 26.6 (18–39) | 73.5 (53.8–98.8) | 41.67% female | 24 | Tablet | EM |
| [Chin 1995](#5) | 200, fasted | 22–41 | NR | 33.34% female | 9 | Tablet | EM |
| [Craven 1983](#5) | 1200, multiple dose, fed | NR | NR | NR | 2 | Tablet | EM |
| [Craven 1983](#5) | 800, multiple dose, fed | NR | NR | NR | 2 | Tablet | EM |
| [Daneshmend 1981](#5) | 200, fed | NR | NR | NR | NR | Tablet | EM |
| [Daneshmend 1981](#5) | 400, fed | NR | NR | NR | NR | Tablet | EM |
| [Daneshmend 1983](#5) | 200, fasted | 25 (21–46) | NR | Male | 8 | Tablet | EM |
| [Daneshmend 1983](#5) | 200, multiple dose, fasted | 25 (21–46) | NR | Male | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 200, fed | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 200, profile 1, fasted | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 400, fasted | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 400, fed | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 600, fasted | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 600, fed | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 800, fasted | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Daneshmend 1984](#5) | 800, fed | 23 (20–31) | 64 (50–75) | 62.5% female | 8 | Tablet | EM |
| [Greenblatt 1998](#5) | 200 twice daily for 5 days, fed | 18–38 | NR | NR | 8 | Tablet | EM |
| [Heel 1982](#5) | 100, fasted | NR | NR | NR | 12 | Tablet | EM |
| [Heel 1982](#5) | 200, fasted | NR | NR | NR | 12 | Tablet | EM |
| [Heel 1982](#5)<sup>+</sup> | 200, fasted | NR | NR | NR | 12 | Solution | EM |
| [Heel 1982](#5) | 400, fasted | NR | NR | NR | 12 | Tablet | EM |
| [Huang 1986](#5) | 200, fasted | 20 (18–25) | 76.4 (61.2–95.3) | Male | 23 | Tablet | EM |
| [Huang 1986](#5)<sup>+</sup> | 200, profile 1, fasted | 20 (18–25) | 76.4 (61.2–95.3) | Male | 12 | Solution | EM |
| [Huang 1986](#5)<sup>+</sup> | 200, profile 2, fasted | 20 (18–25) | 76.4 (61.2–95.3) | Male | 23 | Solution | EM |
| [Huang 1986](#5)<sup>+</sup> | 400, fasted | 20 (18–25) | 76.4 (61.2–95.3) | Male | 12 | Solution | EM |
| [Huang 1986](#5)<sup>+</sup> | 800, fasted | 20 (18–25) | 76.4 (61.2–95.3) | Male | 12 | Solution | EM |
| [Knupp 1993](#5) | 200, fasted | 30 (24–36) | 78.8 | Male | 12 | Tablet | EM |
| [Männistö 1982](#5) | 200, fed | 24 (22–26) | 62 (55–70) | 50% female | 10 | Tablet | EM |
| [Männistö 1982](#5) | 200, profile 1, fasted | 24 (22–26) | 62 (55–70) | 50% female | 10 | Tablet | EM |
| [Männistö 1982](#5) | 200, profile 2, fasted | 24 (22–26) | 62 (55–70) | 50% female | 10 | Tablet | EM |
| [Männistö 1982](#5) | 200, profile 3, fasted | 24 (22–26) | 62 (55–70) | 50% female | 10 | Tablet | EM |
| [Männistö 1982](#5) | 200, with juice, fasted | 24 (22–26) | 62 (55–70) | 50% female | 10 | Tablet | EM |
| [Patel 2011](#5) | 200, multiple dose, fasted | 36 (22–43) | 74.7 (50.1–95) | 19% female | 15 | Tablet | EM |
| [Piscitelli 1991](#5) | 400, fasted | 18–30 | NR | Male | 6 | Tablet | EM |
| [Polk 1999](#5) | 400, fasted | 23 (19–41) | 77.4 (64.2–99.8) | Male | 12 | Tablet | EM |
| [Sadeghnia 2005](#5) | 400, profile 1, fasted | 23–29 | 59–78 | Male | 12 | Tablet | EM |
| [Sadeghnia 2005](#5) | 400, profile 2, fasted | 23–29 | 59–78 | Male | 12 | Tablet | EM |
| [Sekar 2008](#5) | 200 twice daily for 4 days, fed | NR | NR | NR | NR | Tablet | EM |
| [Solomon 2007](#5) | 400, profile 1, fasted | 23.2 (18–45) | NR | Male | 24 | Tablet | EM |
| [Solomon 2007](#5) | 400, profile 2, fasted | 23.2 (18–45) | NR | Male | 24 | Tablet | EM |
| [Sriwiriyajan 2007](#5)<sup>+</sup> | 400, fasted | 33.7 (22–55) | NR | 75% female | 12 | Tablet | EM |
| [Tiseo 1998](#5)<sup>+</sup> | 200 once daily for 7 days, fasted | NR | NR | NR | 21 | Tablet | EM |
| [U.S. FDA 1998](#5) | 200, profile 1, fasted | NR | NR | NR | 23 | Tablet | EM |
| [U.S. FDA 1998](#5) | 200, profile 1, fed | NR | NR | NR | 39 | Tablet | EM |
| [U.S. FDA 1998](#5) | 200, profile 2, fasted | NR | NR | NR | 39 | Tablet | EM |
| [U.S. FDA 1998](#5) | 200, profile 2, fed | NR | NR | NR | 39 | Tablet | EM |
| [U.S. FDA 1998](#5) | 200, profile 3, fasted | NR | NR | NR | 39 | Tablet | EM |
| [Van der Meer 1980](#5) | 200, control, fasted | 28–42 | NR | NR | 3 | Tablet | EM |
| [Weiss 2022](#5) | 400, fasted | 27.34 (20–48) | 74.44 (57.5–100) | Male | 12 | Tablet | EM |
| [Wire 2007](#5) | 200, multiple dose, fasted | NR | NR | NR | 15 | Tablet | EM |
| [Yuen 1999](#5) | 200, profile 1, fasted | NR | NR | NR | 18 | Tablet | EM |
| [Yuen 1999](#5) | 200, profile 2, fasted | NR | NR | NR | 18 | Tablet | EM |

**Table 2:**<a name="table-2"></a> Clinical ketoconazole concentration-time profiles used for model building and verification. \*: Single oral dose unless otherwise specified; EM: extensive metabolizer; NR: not reported; <sup>+</sup>: data used for model building. EM is the model default when study-specific CYP2D6 information is not available. Food conditions are retained in the dose and schedule field.
