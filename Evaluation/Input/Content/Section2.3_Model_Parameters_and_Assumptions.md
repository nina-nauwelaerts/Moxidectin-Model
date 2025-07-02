### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The model parameter `Specific intestinal permeability` was calculated by default based on the lipophilicity. Predicted aqueous solubility ([Drugbank](#main-references), see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)) was set as default solubility. For simplicity, all oral administrations were modelled as solution. Food effects were not specifically evaluated, as they did not result in clinically significant effect. Nevertheless, data for fasted and fed conditions were used to develop and verify the PBPK model. For fed conditions, a standard high-fat breakfast event was implemented according to the study information.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

Fraction unbound was reported approximately 0.00078 ([Wood 2024](#main-references), see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). `Lipophilicity` was optimized within the range of measured values (4.30-6.00) to find a best match of simulated to observed moxidectin PK profile data. After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `PK-Sim Standard` and cellular permeability calculation by `PK-Sim Standard` for moxidectin.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

Data regarding metabolism and elimination of moxidectin is limited. Retrograde calculation of clearance, assuming 7% of clearance is CYP3A4-mediated, resulted in an intrinsic clearance of 36 µL/min/mg protein ([Wood 2024](#main-references)). The majority of clearance (93%) was assumed to be biliary clearance. Retrograde calculation based on an apparent total clearance of 2760-3506 mL/h for healthy volunteers results in an estimated biliary clearance of 40 mL/h/kg ([FDA 2018](#main-reference)). 

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

This is the result of the final parameter identification.

| Model Parameter      | Optimized Value | Unit |
| -------------------- | --------------- | ---- |
| `Lipophilicity` | 4.60                | Log units     |

