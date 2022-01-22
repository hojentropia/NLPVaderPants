# NLPVaderPants

We do a NLP sentiment analysis of comments from Levi's pants. We used the VADER model, which is suited for [social networks comments](https://ojs.aaai.org/index.php/ICWSM/article/view/14550) analysis. 

We do the same analysis for comments before and during COVID, to look for any difference.

Basic ETL was done and the Stopwords were removed. We used the langid library to identify the language of the comment, and we applied the model only on English comments.

To visualize the results, we used a boxplot and some barplots. We saw that the overall sentiment was slightly better during COVID. 

![Boxplot](https://github.com/tograh/testrepository/master/3DTest.png 570)
