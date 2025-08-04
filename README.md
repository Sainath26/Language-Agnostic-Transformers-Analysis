# Language-Agnostic-Transformers-Analysis

This study in collabration with Oliver Wyman tries to answer the following questions:

**Q1.** For a downstream task like text classification, is it better to use a monolingual model trained on a single language or a multilingual model exposed to dozens of languages?  
**Notebook:** `Zero_Shot_Analysis.ipynb`

**Q2.** Given that simpler multilingual models remain competitive for classification, how do we pick the best pretrained model?  
**Notebook:** `Embedding_Similarity_Testing.ipynb` implements a tookkit to evaluate embedding quality for downstream classification.

**Toolkit Evalutation**  
View the complete list of models evaluated using the toolkit:

- [English–Chinese](https://sainath26.github.io/Language-Agnostic-Transformers-Analysis/Results/English_Chinese_dashboard.html)
- [English–French](https://sainath26.github.io/Language-Agnostic-Transformers-Analysis/Results/English_French_dashboard.html)
- [English–Spanish](https://sainath26.github.io/Language-Agnostic-Transformers-Analysis/Results/English_Spanish_dashboard.html)
