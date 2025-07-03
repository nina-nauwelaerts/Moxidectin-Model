The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#main-references)). Information regarding the relevant anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([PK-Sim Ontogeny Database Version 7.3](#main-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([Schlender 2016](#main-references)) or otherwise referenced for the specific process.

First, a base mean model was built using clinical Phase I data including single dose oral administration of moxidectin solution in fasted and fed state, as well as single dose oral administration as solution or tablet was used to find an appropriate structure to describe the pharmacokinetics in plasma ([Korth-Bradley 2012b](#main-references)). The mean PBPK model was developed using individuals matching the study demographics. The relative tissue specific expressions of CYP3A4 was considered. The aim of the current work was to establish a PBPK model of moxidectin for its use in tuberculosis. Although moxidectin is not approved yet for this indication, a daily dosing regimen is generally the standard for tuberculosis. Therefore, the model development prioritized prediction of the first day(s) compared to the terminal phase. 

Unknown parameters (see below) were identified using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility. 

Moxidectin is absorbed relatively quick. For simplicity, a dissolved formulation was applied for both solution and tablet formulations.

The model was then verified by simulating ([Cotreau 2003, Kinrade 2018](#main-references)):

- a dose range between 3 mg and 36 mg 
- fed and fasted state

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#methods-data).

Details about the structural model and its parameters can be found in  [Section 2.3](#model-parameters-and-assumptions).

