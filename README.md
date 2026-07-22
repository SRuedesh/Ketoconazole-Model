# Ketoconazole-Model
Whole-body parent-metabolite PBPK model of ketoconazole, N-deacetylketoconazole and N-deacetyl-N-hydroxyketoconazole as CYP3A4 and P-gp drug-drug interaction perpetrators.

This repository contains the ketoconazole model originally published by Marok et al. [[1](#references)].

The model was developed and evaluated using published clinical plasma pharmacokinetic data compiled by Marok et al. [[1](#references)], including oral single-dose and multiple-dose ketoconazole data by Daneshmend et al. [[8](#references), [9](#references), [10](#references), [11](#references)], Heel et al. [[7](#references)], Huang et al. [[12](#references)], Polk et al. [[13](#references)], Boyce et al. [[14](#references)], Tiseo et al. [[15](#references)], Craven et al. [[16](#references)], Männistö et al. [[17](#references)], Greenblatt et al. [[18](#references)] and Weiss et al. [[2](#references)].

Users of the model are expected to cite the original model publication and the clinical or in vitro source studies when using the model in scientific work, reports or derivative model development:
- [F Z Marok, J-G Wojtyniak, L M Fuhr, D Selzer, M Schwab, J Weiss, W E Haefeli, T Lehr. A Physiologically Based Pharmacokinetic Model of Ketoconazole and Its Metabolites as Drug-Drug Interaction Perpetrators. Pharmaceutics, 2023;15:679.](https://doi.org/10.3390/pharmaceutics15020679)

Model note: The FMO3 K<sub>m</sub> value of 1.17 µmol/L implemented for N-deacetylketoconazole is correct. The corresponding value reported by Marok et al. [[1](#references)] is erroneous.

This ketoconazole model is intended to describe ketoconazole and metabolite pharmacokinetics after oral ketoconazole administration and to support DFI and DDI simulations involving CYP3A4 and P-gp inhibition.

The presented model includes the following features:

- oral solution, capsule-as-solution and tablet formulations,
- fasted and fed administration scenarios,
- formation of N-deacetylketoconazole and N-deacetyl-N-hydroxyketoconazole,
- metabolism by CYP3A4, arylacetamide deacetylase and UGT1A4,
- P-gp transport and CYP3A4/P-gp inhibition,
- parent-metabolite DDI perpetrator behavior.

## Repository files
This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (*.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation_plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found in the [latest release in this repository](https://github.com/Open-Systems-Pharmacology/Ketoconazole-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found in the [latest OSP PBPK Model Library release](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] F Z Marok, J-G Wojtyniak, L M Fuhr, D Selzer, M Schwab, J Weiss, W E Haefeli, T Lehr. A Physiologically Based Pharmacokinetic Model of Ketoconazole and Its Metabolites as Drug-Drug Interaction Perpetrators. Pharmaceutics, 2023;15:679. doi: [10.3390/pharmaceutics15020679](https://doi.org/10.3390/pharmaceutics15020679).

[2] J Weiss, K I Foerster, M Weber, J Burhenne, G Mikus, T Lehr, W E Haefeli. Does the circulating ketoconazole metabolite N-deacetyl ketoconazole contribute to the drug-drug interaction potential of the parent compound? Eur J Pharm Sci, 2022;169:106076. [DOI](https://doi.org/10.1016/j.ejps.2021.106076).

[3] T Fukami, A Iida, K Konishi, M Nakajima. Human arylacetamide deacetylase hydrolyzes ketoconazole to trigger hepatocellular toxicity. Biochem Pharmacol, 2016;116:153-161. doi: [10.1016/j.bcp.2016.07.007](https://doi.org/10.1016/j.bcp.2016.07.007).

[4] W Fitch, T Tran, M Young, L Liu, Y Chen. Revisiting the Metabolism of Ketoconazole Using Accurate Mass. Drug Metab Lett, 2009;3:191-198. doi: [10.2174/187231209789352085](https://doi.org/10.2174/187231209789352085).

[5] D Schwab, H Fischer, A Tabatabaei, S Poli, J Huwyler. Comparison of in Vitro P-Glycoprotein Screening Assays: Recommendations for Their Use in Drug Discovery. J Med Chem, 2003;46:1716-1725. [DOI](https://doi.org/10.1021/jm021012t).

[6] K Bourcier, R Hyland, S Kempshall, R Jones, J Maximilien, N Irvine, B Jones. Investigation into UDP-Glucuronosyltransferase enzyme kinetics of imidazole- and triazole-containing antifungal drugs in human liver microsomes and recombinant UGT enzymes. Drug Metab Dispos, 2010;38:923-929. doi: [10.1124/dmd.109.030676](https://doi.org/10.1124/dmd.109.030676).

[7] R C Heel, R N Brogden, A Carmine, P A Morley, T M Speight, G S Avery. Ketoconazole: A Review of its Therapeutic Efficacy in Superficial and Systemic Fungal Infections. Drugs, 1982;23:1-36. doi: [10.2165/00003495-198223010-00001](https://doi.org/10.2165/00003495-198223010-00001).

[8] T K Daneshmend, D W Warnock, A Turner, C J C Roberts. Pharmacokinetics of ketoconazole in normal subjects. J Antimicrob Chemother, 1981;8:299-304. doi: [10.1093/jac/8.4.299](https://doi.org/10.1093/jac/8.4.299).

[9] T K Daneshmend, D W Warnock. Clinical Pharmacokinetics of Ketoconazole. Clin Pharmacokinet, 1988;14:13-34. doi: [10.2165/00003088-198814010-00002](https://doi.org/10.2165/00003088-198814010-00002).

[10] T K Daneshmend, D W Warnock, E M Johnson, G Parker, M D Richardson, C J C Roberts. Multiple dose pharmacokinetics of ketoconazole and their effects on antipyrine kinetics in man. J Antimicrob Chemother, 1983;12:185-188. doi: [10.1093/jac/12.2.185](https://doi.org/10.1093/jac/12.2.185).

[11] T K Daneshmend, D W Warnock, M D Ene, E M Johnson, M R Potten, M D Richardson, P J Williamson. Influence of food on the pharmacokinetics of ketoconazole. Antimicrob Agents Chemother, 1984;25:1-3. doi: [10.1128/AAC.25.1.1](https://doi.org/10.1128/AAC.25.1.1).

[12] Y-C Huang, J L Colaizzi, R H Bierman, R Woestenborghs, J J P Heykants. Pharmacokinetics and dose proportionality of ketoconazole in normal volunteers. Antimicrob Agents Chemother, 1986;30:206-210. doi: [10.1128/AAC.30.2.206](https://doi.org/10.1128/AAC.30.2.206).

[13] R E Polk, M A Crouch, D S Israel, A Pastor, B M Sadler, G E Chittick, W T Symonds, W Gouldin, Y Lou. Pharmacokinetic interaction between ketoconazole and amprenavir after single doses in healthy men. Pharmacotherapy, 1999;19:1378-1384. [DOI](https://doi.org/10.1592/phco.19.18.1378.30905).

[14] M J Boyce, K J Baisley, S J Warrington. Pharmacokinetic interaction between domperidone and ketoconazole leads to QT prolongation in healthy volunteers: A randomized, placebo-controlled, double-blind, crossover study. Br J Clin Pharmacol, 2012;73:411-421. doi: [10.1111/j.1365-2125.2011.04093.x](https://doi.org/10.1111/j.1365-2125.2011.04093.x).

[15] P J Tiseo, C A Perdomo, L T Friedhoff. Concurrent administration of donepezil HCl and ketoconazole: Assessment of pharmacokinetic changes following single and multiple doses. Br J Clin Pharmacol, 1998;46 Suppl 1:30-34. doi: [10.1046/j.1365-2125.1998.0460s1030.x](https://doi.org/10.1046/j.1365-2125.1998.0460s1030.x).

[16] P C Craven, J R Graybill, J H Jorgensen, W E Dismukes, B E Levine. High-dose ketoconazole for treatment of fungal infections of the central nervous system. Ann Intern Med, 1983;98:160-167. doi: [10.7326/0003-4819-98-2-160](https://doi.org/10.7326/0003-4819-98-2-160).

[17] P T Männistö, R Mäntylä, S Nykänen, U Lamminsivu, P Ottoila. Impairing effect of food on ketoconazole absorption. Antimicrob Agents Chemother, 1982;21:730-733. doi: [10.1128/AAC.21.5.730](https://doi.org/10.1128/AAC.21.5.730).

[18] D J Greenblatt, C E Wright, L L von Moltke, J S Harmatz, B L Ehrenberg, L M Harrel, K Corbett, M Counihan, S Tobias, R I Shader. Ketoconazole inhibition of triazolam and alprazolam clearance: Differential kinetic and dynamic consequences. Clin Pharmacol Ther, 1998;64:237-247. doi: [10.1016/S0009-9236(98)90172-2](https://doi.org/10.1016/S0009-9236(98)90172-2).
