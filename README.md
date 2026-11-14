# Who Should We Target? Predicting High Grocery Spenders for Armando Testa

IS 4487 final project, Fall 2026. Team: Xander Patterson, Andrew Johnson, Hunter Voung and Eddie Yoshioka.

We use the BLS Consumer Expenditure Survey to predict which U.S. households spend more than the median (\$150 a week) on groceries, from age, income, region, household size and household type. We compare logistic regression, a decision tree and k-nearest neighbors and turn the best one into a targeting recommendation for Armando Testa's grocery clients.

| File | What it is |
|---|---|
| `final_project_armando_testa.ipynb` | The full analysis, following CRISP-DM, run top to bottom with outputs |
| `data/fmli24.zip` | The four household (FMLI) files from the BLS 2024 Interview download, unchanged. Source: https://www.bls.gov/cex/pumd_data.htm |
| `data/mtbi244.zip` | The detailed expenditure file (MTBI) for October to December 2024 interviews from the same download, unchanged. Used in Section 4 |
| `charts/` | Charts 1 to 6, saved by the notebook (Section 10) and used in the slides under the same numbers |
| `IS 4487 Final Project.pptx` | Presentation slides, with speaker notes |
| `IS 4487 Final Project Slides.pdf` | The same slides as a PDF |

To run the notebook, keep the `data` folder next to it. In Colab, make a folder called `data` and upload `fmli24.zip` and `mtbi244.zip` into it. It uses pandas, numpy, matplotlib, seaborn and scikit-learn.
