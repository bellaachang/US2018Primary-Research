# Probabilistic Inference on 2018 U.S. Primary Elections
For my group final project in DATA 102: Data, Inference, and Decisions, my group and I chose to research FiveThirtyEight's dataset on the 2018 U.S. primaries: https://github.com/fivethirtyeight/data/tree/master/primary-candidates-2018. 

Specifically, we conducted in-depth statistical analysis on two research questions, oriented around two major concepts in probabilistic decision-making:
1) [Multiple Hypothesis Testing] Did endorsements from groups supporting specific causes affect the chance of winning in the 2018 primary?
2) [Bayesian Hierarchical Modeling] Can we fit a Bayesian mixture model to describe the ideological inclusiveness of a candidate’s campaign platform based on the number of endorsements they received in the 2018 Democratic primaries?

In addressing the first question, we conducted a comprehensive assessment involving the examination of p-values for 7 distinct hypotheses. Subsequently, we applied both Bonferroni and Benjamini-Yekutieli corrections to ascertain the family-wise error rate (FWER) and false discovery rate (FDR) correspondingly, in direct relevance to the research question. Ultimately, our analysis led to the conclusive determination that endorsements indeed wielded a significant impact on the outcome of the 2018 primary elections in the United States, encompassing both the Democratic and Republican factions.

Regarding the second question, we engineered an intricate Bayesian mixture model within the PyMC framework. This model was designed to evaluate three latent variables, inferred from the count of endorsements presumed to follow a Binomial distribution within our dataset. Subsequent to model formulation, we conducted inferences based on empirical data and gauged the credible intervals for the posterior distributions corresponding to the latent variables encapsulated within the model.

All analyses can be found in our 17-page written report, attached as a PDF within this repo. Code is also available in a Jupyter Notebook.

Collaborators: Michelle Chang ('24, DS & Business Administration), Chris He ('24, DS & Applied Math), Joellene Yap ('24, DS & Media Studies)
