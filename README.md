# DivSumm summarization dataset

Dataset introduced in the paper: Analyzing the Dialect Diversity in Multi-document Summaries (COLING 2022)
_Olubusayo Olabisi, Aaron Hudson, Antonie Jetter, Ameeta Agrawal_


DivSumm is a novel dataset consisting of dialect-diverse tweets and human-written extractive and abstractive summaries. It consists of 90 tweets each on 25 topics in multiple English dialects (African-American, Hispanic and White), and two reference summaries per input."



## Directories

input_docs - 90 tweets per topic evenly distributed among 3 dialects; total 25 topics

abstractive - Two annotators were asked to summarize each topic in 5 sentences using their own words. 

extractive - Two annotators were asked to select 5 tweets from each topic that summarized the input tweets.


## Paper


You can find our paper [here](https://aclanthology.org/2022.coling-1.542/). If you use this dataset in your work, please cite our paper:


    @inproceedings{olabisi-etal-2022-analyzing,
        title = "Analyzing the Dialect Diversity in Multi-document Summaries",
        author = "Olabisi, Olubusayo  and Hudson, Aaron  and Jetter, Antonie  and Agrawal, Ameeta",
        booktitle = "Proceedings of the 29th International Conference on Computational Linguistics",
        month = oct,
        year = "2022",
    }
