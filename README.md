<h1>Finding the sweet spot: Learners’ productive knowledge of mid-frequency lexical items</h1>

This public github repository contains some of the code for the paper *Finding the sweet spot: The intersection of lexical breadth and depth in a learner corpus* by Ben Naismith and Alan Juffs, members of the [University of Pittsburgh Data Mining Research Group](https://github.com/ELI-Data-Mining-Group) who work primarily with the Pittsburgh English Language Institute Corpus (PELIC).

All of the code is written using Python 3.8 in Jupyter notebooks. There are three notebooks which address different aspects of the project, and they follow a sequential order, loading pickles from the previous notebooks:  

  - [**1_COCA_dataset.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/1_COCA_dataset.ipynb) - creating of the 'key families' dataset based on COCA frequency information
  - [**2_PELIC_dataset.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/2_PELIC_dataset.ipynb) - collecting occurrences of the 'key families' items in PELIC
  - [**3_Concordances.ipynb**](https://github.com/ELI-Data-Mining-Group/Lexical_depth_Naismith_et_al_2020/blob/master/3_Concordances.ipynb) - creating a concordancer and dataframe based on the PELIC dataset

#### Important notes:
- This code in intended to make public the dataset so that others may use it for replication or research. The code for the statistical analysis of the paper is not included, e.g. in relation to the human annotations, dictionary/corpus look ups, or Mutual Information measurements.
- The frequency information from COCA referenced here is not freely available but can be purchased at https://corpus.byu.edu/. Without this data you will be able to see samples of the output of the Jupyter notebooks but will not be able to run them completely.

#### Abstract:
Research into vocabulary knowledge often differentiates between breadth (how many words a person knows) and depth (how well the words are known). Both theoretical categories are essential for understanding language learners' lexical development but how the different aspects of vocabulary knowledge interconnect has not received the same attention as each individual dimension (Haomin & Bilü, 2017), especially in terms of productive knowledge (Mantyla & Huhta, 2014).
This study analyzes lexis from mid-frequency lemmas in the K3-K9 frequency bands from the learner corpus PELIC (Juffs et al., 2020). Critically for learners, mastery of lexis in this frequency range is essential for achieving the English proficiency required for university study. From these mid-frequency items, a dataset of 7,554 tokens were collected from word families with multiple derivations and manually annotated. The findings show that compared to expert speaker texts in the Corpus of Contemporary American English (COCA; Davies, 2008-), learners overuse verb forms and underuse noun forms of these lexical items. Moreover, a strong correlation exists between collocational accuracy and derivational accuracy. These patterns provide evidence of the interplay between breadth and depth in learners’ productive vocabulary usage, suggesting that increased lexical depth will naturally lead to greater lexical breadth and vice versa. Pedagogical implications reaffirm the importance of developing learners’ explicit morphological awareness (Ishikawa, 2019) and collocational accuracy (Crossley et al., 2015). Suggestions for mid-frequency lexical items to prioritize in language learning are also provided, with a view to helping learners achieve academic readiness.


**Key words:** Collocation, Derivation, Learner corpus, Lexical breadth, Lexical depth, Lexical knowledge


#### References:
- **Crossley, S. A., Salsbury, T., Mcnamara, D. S.** (2015). Assessing Lexical Proficiency Using Analytic Ratings: A Case for Collocation Accuracy. *Applied Linguistics, 36*(5), 570-590.  
- **Friedline, B. E.** (2011) Challenges in the second language acquisition of derivational morphology: From theory to practice. *Doctoral dissertation*, University of Pittsburgh.  
- **Haomin, Z. & Bilü, Z.** (2017). Multi-faceted morphological awareness and vocabulary knowledge in English as a second language learners: A multivariate analysis. *Chinese Journal of Applied Linguistics, 40*(1), 42-55.  
- **Ishikawa, K. (2019).** Incidental and explicit learning of L2 derivational morphology and the nature of acquired knowledge. *Applied Psycholinguistics, 40*(6), 1377-1404.  
- **Mantyla, K. & Huhta, A.** (2014). Knowledge of word parts. In J. Milton, & T. Fitzpatrick (Eds.), *Dimensions of vocabulary knowledge* (pp. 45-59). UK: Palgrave Macmillan.  
- **Schmitt, N.** (2010). *Researching vocabulary: A vocabulary research manual.* UK: Palgrave Macmillan.  

#### Copyright:
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Finding the sweet spot: The intersection of lexical breadth and depth in a learner corpus</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Ben Naismith</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
