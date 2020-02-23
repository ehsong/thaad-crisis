# thaad-crisis

## web crawling and word frequency counts
Word frequency counts of news headlines on THAAD in South Korean media. The notebook includes the code used to crawl the web portal Naver to query terms and collect news headlines within a time period. The note book is [here](https://github.com/ehsong/thaad-crisis/blob/master/Part1_Naver_News_Corpus.ipynb).

## examining shared links
The notebook contains code I used to examine tweets that included terms on China and THAAD. I examined the web sources of the news shared on twitter, and expanded bit.ly links to examine actual link sources. The notebook is [here](https://github.com/ehsong/thaad-crisis/blob/master/Part2_Twitter_Corpus.ipynb).

## sentiment analysis using lexicons
To further understand sentiment towards China across two time frames, I preprocessed about 0.5 million tweet corpus and then conducted sentiment analysis by using the [Korean Sentiment Lexicon 한국 감성 사전](https://github.com/park1200656/KnuSentiLex) which has 6K positive and negative unigram terms. Using the lexicon, I derived the polarity score for each tweet, and then plotted the proportion of positive and negative tweets out of total tweets were crawled. The notebook where I preprocessed the tweets is [here](https://github.com/ehsong/thaad-crisis/blob/master/text_preprocessing_modules.ipynb), the function for caculating the polarity score is [here](https://github.com/ehsong/thaad-crisis/blob/master/sent_module.ipynb) and the final plot is [here](https://github.com/ehsong/thaad-crisis/blob/master/run_senti.ipynb).

## APSA presentation slides
This project was part of a research project examining the effects of media reporting on pollution attribution in South Korea on public sentiment towards China, and was presented at Annual Political Science Association Conference on August 2019. For a summary of results and the literature, please see the poster link [here](https://apsa2019-apsa.ipostersessions.com/default.aspx?s=DF-1D-34-3D-64-33-21-12-B0-42-57-A1-87-AC-68-E1). 
