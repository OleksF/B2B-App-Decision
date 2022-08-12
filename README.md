# B2B-App-Decision

A minimalist interactive [web page](https://oleksf.github.io/B2B-App-Decision/) serving as a proof of concept for data hierarchies being folded out as interactive web elements in e.g. a custom dashboard. Hierarchy links mapped to corresponding drill-down analysis with charts + text, with options to change variables with a dropdown. Built as a single interactive page, so no notable load times on interaction; all interactive functionality is in `index.html` in the script tag (some day might refactor this), running on D3.js. The data is loaded in from an external source (in this case, the csv file).

Not intended as a full data viz demo--pretty high cognitive load as it's currently built.

Demo data based on a study of B2B app development intent among execs (referenced below).

---

All datasets herein are derivative of...

```
Kunal Swani,
To app or not to app: A business-to-business seller's decision,
Industrial Marketing Management,
Volume 93,
2021,
Pages 389-400,
ISSN 0019-8501,
https://doi.org/10.1016/j.indmarman.2020.05.033.
(https://www.sciencedirect.com/science/article/pii/S0019850119311149)
Abstract: Although business-to-business (B2B) selling firms increasingly realize the benefits of adoption and usage of B2B mobile applications (apps), few studies examine this topic. Building on the technology organization environment and the technology acceptance model adoption frameworks, this research provides an integrative framework to identify and investigate the key determinants of B2B mobile apps for sellers that have not implemented B2B mobile apps for their buyers to use in their decision making. The results from 360 marketing executives at B2B selling firms indicate that perceived usefulness, top management support, and competitive pressure positively influence the decision to adopt B2B mobile apps in the near future. In addition, relative advantage and perceived ease of use indirectly affect adoption of B2B mobile apps through perceived usefulness. The research findings provide several theoretical and managerial implications related to B2B mobile apps adoption.
Keywords: B2B mobile apps; Technology organization environment (TOE) framework; Technology acceptance model (TAM); Survey method; Technology adoption
```

The survey dataset in this repo is a derivative of the associated [Data for: To app or not to app: A business-to-business seller’s decision](https://data.mendeley.com/datasets/ctbcxcmnfj/3) by Kunal Swani, used under [CC BY NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/). The survey dataset in this repo is licensed under [CC BY NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/) by Oleksandr Firsov.

The remaining data files are created from information in the paper. I make no claims to any IP in them, nor take responsibility for anything you do as a result. Do what you will, at your own risk and responsibility.
