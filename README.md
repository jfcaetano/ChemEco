
# HS-ChemEco: Environmental Price Prediction via Interpretable Machine Learning Models of Chemical Emissions

[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs13321--026--01286--3-blue)](https://doi.org/10.1186/s13321-026-01286-3)
[![Journal](https://img.shields.io/badge/Journal-Cheminformatics-005571)](https://link.springer.com/journal/13321)
[![Open Access](https://img.shields.io/badge/Open%20Access-Article-orange.svg)](https://doi.org/10.1186/s13321-026-01286-3)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Online Tool](https://img.shields.io/badge/Online%20Tool-HS--ChemEco-2ea44f)](https://www.holoss.com/tools/HSChemEco.html)

HS-ChemEco is a machine learning-powered tool that predicts Environmental Price (EP) values (`Lower`, `Median`, `Upper`) for chemical substances based on their SMILES representation and environmental emission medium. The model provides **per-sample uncertainty estimates** by combining ensemble standard deviation and benchmark R²-based error.

Environmental Prices quantify the social costs of pollution, expressed in euros per kilogram (€/kg) of emitted substance. The model is based on the **Environmental Prices Handbook** published by [CE Delft](https://cedelft.eu/publications/environmental-prices-handbook-2024-eu27-version/).

---

<div align="center">
  <img src="Supporting Information/Graphical_Abstract.png" alt="HS-ChemEco Graphical Abstract" width="433" height="188">
</div>

<div align="center">
  <h2>⚙️ <a href="https://www.holoss.com/tools/HSChemEco.html">Access the Online Prediction Tool</a></h2>
</div>

---

## Tool Features

🌱 Predicts Environmental Price values (€/kg) directly from SMILES.

🌊 Supports four environmental emission compartments:

- Air
- Soil
- Inland water
- Marine water

🔬 Uses molecular descriptors and chained Random Forest regression models.

🧪 Incorporates chemistry-aware data augmentation.

📊 Provides model interpretability through SHAP and Partial Dependence Plots (PDP).

📉 Provides per-sample prediction uncertainty estimates.

🎯 Achieves an overall test R² of 0.90 ± 0.03.

---

## 📄 Scientific Publication

This repository accompanies the peer-reviewed research article published in the **Journal of Cheminformatics** (Springer Nature).

- **Journal:** Journal of Cheminformatics
- **Volume:** 18
- **Article number:** 168
- **Publication date:** 23 November 2026
- **DOI:** [10.1186/s13321-026-01286-3](https://doi.org/10.1186/s13321-026-01286-3)
- **Access:** Open Access

[Read the full article](https://link.springer.com/article/10.1186/s13321-026-01286-3)

---

## 📚 Citation

If you use HS-ChemEco, its methodology, code, or predictions in your research, please cite the following publication:

> Ferraz-Caetano, J., Paula, M., Nogueira, A., Tamilazhaki, L., Esteban, P., & Ferreira, G. (2026). HS-ChemEco: environmental price prediction via interpretable machine learning models of chemical emissions. *Journal of Cheminformatics*, **18**, 168. https://doi.org/10.1186/s13321-026-01286-3

### BibTeX

```bibtex
@article{FerrazCaetano2026HSChemEco,
  author  = {Ferraz-Caetano, José and
             Paula, Marcella and
             Nogueira, António and
             Tamilazhaki, Lingasamy and
             Esteban, Pablo and
             Ferreira, Germán},
  title   = {{HS-ChemEco}: Environmental price prediction via
             interpretable machine learning models of chemical emissions},
  journal = {Journal of Cheminformatics},
  year    = {2026},
  volume  = {18},
  pages   = {168},
  doi     = {10.1186/s13321-026-01286-3},
  url     = {https://doi.org/10.1186/s13321-026-01286-3}
}
```
---

## License

HS-ChemEco is released under the [MIT License](LICENSE).

The source code may be freely used, modified, and distributed,
including for commercial purposes, provided that the original
copyright and licence notice are retained.

---

<div align="center">
  <a href="https://www.holoss.com">HOLOSS — Holistic and Ontological Solutions for Sustainability</a>
</div>
  <a href="https://www.jfcaetano.com">Developed by José Ferraz-Caetano</a>
</div>
