# NOMA Performance in α-μ and Mixed Fadings: Exact Formulations and Accurate Approximations

[![DOI](https://zenodo.org/badge/1452061688.svg)](https://doi.org/10.5281/zenodo.24095405)

Code accompanying the article:

> M. C. Luna Alvarado, C. R. Nogueira da Silva, and M. D. Yacoub, "NOMA
> Performance in α-μ and Mixed Fadings: Exact Formulations and Accurate
> Approximations," *IEEE Open Journal of the Communications Society*, vol. 6,
> pp. 8688–8697, 2025.
> DOI: [10.1109/OJCOMS.2025.3621557](https://doi.org/10.1109/OJCOMS.2025.3621557)

## Contents

| File | Description | Figures in the paper |
|---|---|---|
| `figures.nb` | Bit error rate (BER) of the NOMA system versus SNR, including the effect of imperfect successive interference cancellation (SIC) | Figs. 1–5 |

The notebook implements the exact BER expressions for NOMA over α-μ fading and
the approximations for mixed product fading, and generates all the figures of
the paper:

- **Fig. 1:** BER of the second user for various values of σ
- **Fig. 2:** BER of the four-user NOMA system for σ = 0.3 and σ = 2.1
- **Fig. 3:** BER of the first user for various values of σ
- **Fig. 4:** BER of the NOMA system over mixed product fading
- **Fig. 5:** BER of user 3 for different combinations of α-μ, κ-μ and extended
  η-μ variates in the mixed product fading

[Analytical results are compared against Monte Carlo simulations included in
the notebook.]

## Requirements

- Wolfram Mathematica 13

## Usage

To plot the figures, open the corresponding notebook and evaluate all cells by clicking on the button Run all. The figures are generated in the order in which they appear in the paper.

## Citation

If you use this code, please cite the article above:

```bibtex
@article{LunaAlvarado2025OJCOMS,
  author  = {Luna Alvarado, Maria Cecilia and Nogueira da Silva, Carlos Rafael and Yacoub, Michel Daoud},
  title   = {{NOMA} Performance in $\alpha$-$\mu$ and Mixed Fadings: Exact Formulations and Accurate Approximations},
  journal = {IEEE Open Journal of the Communications Society},
  volume  = {6},
  pages   = {8688--8697},
  year    = {2025},
  doi     = {10.1109/OJCOMS.2025.3621557}
}
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
