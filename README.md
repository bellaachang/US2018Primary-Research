# Statistical Research on 2018 U.S. Primary Elections
For my group final project in DATA 102: Data, Inference, and Decisions, my group and I chose to research FiveThirtyEight's dataset on the 2018 U.S. primaries: https://github.com/fivethirtyeight/data/tree/master/primary-candidates-2018. 

Specifically, we conducted in-depth statistical analysis on two research questions, oriented around two major concepts in probabilistic decision-making:
1) [Multiple Hypothesis Testing] Did endorsements from groups supporting specific causes affect the chance of winning in the 2018 primary?
2) [Bayesian Hierarchical Modeling] Can we fit a Bayesian mixture model to describe the ideological inclusiveness of a candidate’s campaign platform based on the number of endorsements they received in the 2018 Democratic primaries?

For the first question, we evaluated 7 hypotheses' p-values and then utilized Bonferroni and Benjamini-Yekutieli correction to find family-wise error rate (FWER) and false discovery rate (FDR) respectively in relation to the research question, ultimately finding the conclusion that endorsements did have a significant effect on winning the 2018 primary in the U.S. for both Democrats and Republicans.

For the second question, we created a complex Bayesian mixture model in PyMC evaluating three hidden variables informed by the number of endorsements, assumed to be a Binomial distribution, in our dataset. We then fit our inferences on our actual data and evaluated the credible intervals for our posterior distributions of the hidden variables in the model.

All analyses can be found in our 17-page written report, attached as a PDF within this repo. Code is also available in a Jupyter Notebook.

Collaborators: Michelle Chang ('24, DS & Business Administration), Chris He ('24, DS & Applied Math), Joellene Yap ('24, DS & Media Studies)
