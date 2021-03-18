# Arabic-Dataset-for-Propaganda-Techniques-Detection

## Inroduction 
Propaganda has been used on social media and online news articles to convince readers to accept biased or false beliefs and ideologies. It is usually used to manipulate citizens' public opinion and influence their attitudes by using psychological and rhetorical techniques, which appeal to the emotions of the audience and use logical fallacies. The detection of propaganda techniques in news articles is the initial step toward limiting the use of propaganda and increase people' aware that online news could be shaped to manipulate their thoughts.

## Dataset
The Arabic propaganda techniques dataset is based on [Fine-Grained Analysis of Propaganda in News Articles](https://propaganda.qcri.org/fine-grained-propaganda-emnlp.html). The dataset provided as news articles where each article contains a list of propaganda techniques and each technique is assoisated with a span in the article. We translated the original English propaganda spans into Arabic. <br>

To the best of our knowledge, there is no Arabic dataset publicly available for propganda techniques. The provided dataset has 7k propaganda spans and consists of three files: train, validation, and test file. Each file provided as a tab speareated file containing the article id, propaganda techniqe (one out of 18 propaganda techniques), begin and offsets for each propaganda span.<br> 

## Evaluation 
The task will be evaluated using Micro-Average F1 score

## Model
We provided a baseline model by fine-tuning AraBERT to classify propaganda techniques and it achieved 60% F1 Score.

## License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## BibText
```

```


## Acknowledgment
Special thank to [Propaganda Analysis Project (PAP)](https://propaganda.qcri.org/fine-grained-propaganda-emnlp.html) for their support and giving us the English propaganda dataset. 
