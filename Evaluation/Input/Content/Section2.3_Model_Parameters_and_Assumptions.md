### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

There is no absorption process since inulin was administered intravenously

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

The standard vascular properties of the different tissues (hydraulic conductivity, pore radii, fraction of flow via large pores) and standard lymph and fluid recirculation flow rates from PK-Sim were  used ([Niederalt 2018](#5-references)). 

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

Inulin is renally excreted via glomerular filtration. The standard glomerular filtration rate from the PK-Sim library was used (GFR fraction = 1). 

### Tissue Concentrations <a id="model-parameters-and-assumptions-tissue-concentrations"></a>

For the comparison with experimental data the parameters `Fraction of blood for sampling` used in the Observer for the tissue concentrations were set for all organs to 0.18.  This value is based on the parameter identification for different compounds reported in Ref. ([Niederalt 2018](#5-references)) for comparison with tissue dissection data. (The parameter `Fraction of blood for sampling` specifies residual blood in tissue as ratio of blood volume contributing to the measured tissue concentration to the total in vivo capillary blood volume.)

| Model Parameter                               | Value | Unit |
| --------------------------------------------- | ----- | ---- |
| `Fraction of blood for sampling` (all organs) | 0.18  |      |

Experimentally, gut concentrations (from duodenum  to the cecum) were measured ([Tsuji 1983](#5-references)). In the present evaluation report, the experimental gut concentrations were compared to simulated organ concentrations for small and large intestine separately in the goodness of fit plots as well as in the concentration-time profile plot. 

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

No drug specific parameters were fitted.

