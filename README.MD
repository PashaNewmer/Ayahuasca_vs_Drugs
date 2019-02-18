![Ayahuasca vs Drugs](./Aya.png)


## Problem Statement
Collect posts from 2 subreddits from www.reddit.com, DrugNerd and Ayahuasca, Using Reddit's API. Then using NLP, to train a classifier on which subreddit a given post came from. The accuracy might tell us that people consider Ayahuasca as a sacred medicine or just a drug. We will see if they talking about Ayahuasca differently then about any other drugs.


## The data.
We use Reddit's API to collect data from DrugNerd and Ayahuasca subreddits. The API returns data in a .json format, so we can processing the data in Python. 


## Executive Summary

We can see that two categories 'DrugNerd' and 'Ayahuasca' may be divided with very high accuracy. Among all the methods, logistic regression gave us the highest accuracy. That shows a lot about what people think and say about ayahuasca, definitely separating it from “drugs” category. We can see that people use more words like "experience", "ceremony", "retreat" and "help" when talking about Ayahuasca, that totally confirms that idea.