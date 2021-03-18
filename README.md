# Arabic-Dataset-for-Propaganda-Techniques-Detection

## Inroduction 
Propaganda has been used on social media and online news articles to convince readers to accept biased or false beliefs and ideologies. It is usually used to manipulate citizens' public opinion and influence their attitudes by using psychological and rhetorical techniques, which appeal to the emotions of the audience and use logical fallacies. The classification of propaganda techniques in news articles is a multi-class classification problem where each propaganda span will be associated with at most one propaganda technique. Propaganda techniques detection is the initial step toward limiting the use of propaganda and increase people' aware that online news could be shaped to manipulate their thoughts.

## Dataset
The Arabic propaganda techniques dataset is based on [Fine-Grained Analysis of Propaganda in News Articles](https://propaganda.qcri.org/fine-grained-propaganda-emnlp.html). The dataset provided as news articles where each article contains a list of propaganda techniques and each technique is associated with a span in the article. We translated the original English propaganda spans into Arabic. <br>

To the best of our knowledge, there is no Arabic dataset publicly available for propaganda techniques. The provided dataset has 7k propaganda spans and consists of three files: train, validation, and test file. Each file provided as a tab separated file containing the article id, propaganda technique (one out of 18 propaganda techniques), begin and offsets for each propaganda span.<br> 

## Evaluation 
The task will be evaluated using Micro-Average F1 score

## Model
We provided a baseline model by fine-tuning AraBERT to classify propaganda techniques and it achieved 60% F1 Score.


## COVID-19 Dataset
One of our goals was to detect the most commonly used propaganda techniques in news articles related to the coronavirus (COVID-19) pandemic. Consequently, we have collected 44 news articles from three well known Arabic news outlets, namely Al Arabiya (25 articles), Al Aljazeera  (15 articles), and BBC (4 articles) manually from the official websites from March 1, 2020, until March 30, 2020. Furthermore, 200 spans have been extracted manually from the articles based on local judgments that the spans have a high probability of being propaganda. Then all extracted spans have been saved in a text file.

## License


This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by](http://creativecommons.org/licenses/by/4.0/)


## BibText
```

```


## Acknowledgment
Special thank to [Propaganda Analysis Project (PAP)](https://propaganda.qcri.org/fine-grained-propaganda-emnlp.html) for their support and giving us the English propaganda dataset. 
