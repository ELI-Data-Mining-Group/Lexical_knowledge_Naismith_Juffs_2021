<h1>Finding the sweet spot: Learners’ productive knowledge of mid-frequency lexical items</h1>

**Recommended citation:**  
Naismith, B., & Juffs, A. (2021). Finding the sweet spot: Learners’ productive knowledge of mid-frequency lexical items. _Language Teaching Research_. https://doi.org/10.1177/13621688211020412

This public GitHub repository contains some of the code for the paper cited above. The authors are members of the [University of Pittsburgh Data Mining Research Group](https://github.com/ELI-Data-Mining-Group) who work with the [Pittsburgh English Language Institute Corpus (PELIC)](https://eli-data-mining-group.github.io/Pitt-ELI-Corpus/).

All of the code is written using Python 3.8 in Jupyter notebooks. There are three notebooks which address different aspects of the project, and they follow a sequential order, loading pickle files from the previous notebooks:  

  - [**1_COCA_dataset.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/1_COCA_dataset.ipynb) - creating the 'key families' dataset based on COCA frequency information
  - [**2_PELIC_dataset.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/2_PELIC_dataset.ipynb) - collecting occurrences of the 'key families' items in PELIC
  - [**3_Concordances.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/3_Concordances.ipynb) - creating a concordancer and dataframe based on the PELIC dataset

#### Important notes:
- This code in intended to make public the dataset so that others may use it for replication or research. The code for the statistical analysis of the paper is not included, e.g. in relation to the human annotations, dictionary/corpus look ups, or Mutual Information measurements.
- The frequency information from COCA referenced here is not freely available but can be purchased at https://corpus.byu.edu/. Without this data you will be able to see samples of the output of the Jupyter notebooks but will not be able to run them completely.

#### Abstract:
Research into vocabulary knowledge often differentiates between breadth (how many words a person knows) and depth (how well the words are known). Both theoretical categories are essential for understanding language learners' lexical development but how the different aspects of vocabulary knowledge interconnect has not received the same attention as each individual dimension (Haomin & Bilü, 2017), especially in terms of productive knowledge (Mantyla & Huhta, 2014).
This study analyzes lexis from mid-frequency lemmas in the K3-K9 frequency bands from the learner corpus PELIC (Juffs et al., 2020). Critically for learners, mastery of lexis in this frequency range is essential for achieving the English proficiency required for university study. From these mid-frequency items, a dataset of 7,554 tokens were collected from word families with multiple derivations and manually annotated. The findings showed high rates of collocational and derivational accuracy for the forms learners opted to use. However, compared to expert speaker texts in the Corpus of Contemporary American English (COCA; Davies, 2008-), learners overused the verb forms and underused the noun forms of these lexical items. These patterns provide evidence of the interplay between breadth and depth in learners’ productive vocabulary usage, suggesting that increased lexical depth will naturally lead to greater lexical breadth and vice versa. Pedagogical implications reaffirm the importance of developing learners’ explicit morphological awareness (Ishikawa, 2019) and collocational accuracy (Crossley et al., 2015). Suggestions for mid-frequency lexical items to prioritize in language learning are also provided, with a view to helping learners achieve academic readiness.

**Key words:** Collocation; Derivation; Learner corpus; Lexical breadth; Lexical depth; Lexical knowledge; Vocabulary knowledge


#### References:
- **Crossley, S. A., Salsbury, T., Mcnamara, D. S.** (2015). Assessing Lexical Proficiency Using Analytic Ratings: A Case for Collocation Accuracy. *Applied Linguistics, 36*(5), 570-590.
- **Davies, M.** (2008-). The Corpus of Contemporary American English (COCA): 560 million words, 1990-present. Available at https://corpus.byu.edu/coca/ (accessed October 2018).
- **Haomin, Z. & Bilü, Z.** (2017). Multi-faceted morphological awareness and vocabulary knowledge in English as a second language learners: A multivariate analysis. *Chinese Journal of Applied Linguistics, 40*(1), 42-55.  
- **Ishikawa, K. (2019).** Incidental and explicit learning of L2 derivational morphology and the nature of acquired knowledge. *Applied Psycholinguistics, 40*(6), 1377-1404.
- **Juffs, A., Han, N-R., & Naismith, B.** (2020). The University of Pittsburgh English Language Corpus (PELIC) [Data set]. http://doi.org/10.5281/zenodo.3991977
- **Mantyla, K. & Huhta, A.** (2014). Knowledge of word parts. In J. Milton, & T. Fitzpatrick (Eds.), *Dimensions of vocabulary knowledge* (pp. 45-59). UK: Palgrave Macmillan.  

#### Copyright:
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Finding the sweet spot: The intersection of lexical breadth and depth in a learner corpus</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Ben Naismith</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
