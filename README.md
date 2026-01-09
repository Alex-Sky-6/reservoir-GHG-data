# reservoir-GHG-data
# GHG Emission Factors Dataset (Table S15)

## Description
This dataset contains greenhouse gas (GHG) emission factors and organic burial factors from water surface and drawdown areas. 

The data is transcribed from **Table 2** of **Ning et al. (2025)**. The Global Warming Potential (GWP) values referenced in the dataset align with climate sensitivity standards discussed in **Forster et al. (2021)** (IPCC AR6).

- **Units**:
  - GHG emission rate: mgC(N)/m²/d
  - Organic carbon burial rate: mgC/m²/d
  - GWP: Global Warming Potential

## Data Preview

| Gas | Date | Water Surface GHG Rate | Drawdown Area GHG Rate | Water Surface Burial Rate | Drawdown Area Burial Rate | GWP |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| CO2 | Aug.–Dec. | 327 | 1821 | 395 | 97 | 1 |
| CH4 | Aug.–Dec. | 4.140 | 0.000 | - | - | 34 |
| N2O | Aug.–Sep. | 0.336 | 0.336 | - | - | 298 |
| N2O | Sep.–Oct. | 0.084 | 0.084 | - | - | 298 |
| N2O | Nov.–Dec. | 0.023 | 0.023 | - | - | 298 |

## References

If you use this data, please cite the following sources:

### 1. Source of Data (Table S15)
> Ning, Z., Zhou, Y., He, J., Tang, C., Xu, C. Y., & Chang, F. J. (2025). **Balancing water, power, and carbon: A synergistic optimization framework for mega cascade reservoir operations.** *Renewable Energy*, 243, 122567. https://doi.org/10.1016/j.renene.2025.122567

### 2. Reference for GWP Values
> Forster, P., Storelvmo, T., Armour, K., et al. (2021). **The earth’s energy budget, climate feedbacks, and climate sensitivity.** In V. Masson-Delmotte et al. (Eds.), *Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change* (pp. 923–1054). Cambridge University Press. https://doi.org/10.1017/9781009157896.009

---

## BibTeX

```bibtex
@article{Ning2025,
  title={Balancing water, power, and carbon: A synergistic optimization framework for mega cascade reservoir operations},
  author={Ning, Z. and Zhou, Y. and He, J. and Tang, C. and Xu, C. Y. and Chang, F. J.},
  journal={Renewable Energy},
  volume={243},
  pages={122567},
  year={2025},
  publisher={Elsevier},
  doi={10.1016/j.renene.2025.122567}
}

@incollection{Forster2021,
  title={The earth’s energy budget, climate feedbacks, and climate sensitivity},
  author={Forster, P. and Storelvmo, T. and Armour, K. and others},
  booktitle={Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change},
  editor={Masson-Delmotte, V. and Zhai, P. and Pirani, A. and others},
  pages={923--1054},
  year={2021},
  publisher={Cambridge University Press},
  address={Cambridge, United Kingdom and New York, NY, USA},
  doi={10.1017/9781009157896.009}
}
