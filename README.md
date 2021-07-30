![Header](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/images/breakin-the-binary.jpeg?raw=true)
## Use of inclusive language in the Spanish language
### A case study on the use of _todes_ in Twitter in Santiago de Chile
Analysis made by [Pedro Pablo Errázuriz](https://www.linkedin.com/in/pedropablo-errazuriz/)

### Summary

This research analyses the fuse of the word _todes_ between October 2019 and July 2021. It finds out that, though its use is still minoritary, has grown exponentially, mainly because of events connected to the country's political cicly. As so, its use is still mainly political. 

### Context

For about two decades in different circles has been discussions about the use of inclusive language in the Spanish language. Under the current gramatical rules, the word _todos_ is used to refer only to men, and both to men and women. When refering only to women, the word _todas_ is used. From a femenine perspective, the word invisibilizes women. From a queer perspective, it does the same to non-binary people. Earlier was proposed to use the words _todxs_ and/or _tod@s_, finally gaining traction the word _todes_ because of pronunciability. The use of inclusive language is not reduced to _todes_, but it could be used for any other word (for example _chilenes_ instead of _chilenos_ (Chileans), or _abogades_ instead of _abogados_ (lawyers), but somehow _todes_ has become an emblem of inclusive language, in the same way the singular _they_ has in English. 

### Twitter Scrapping

I used the library [snscrape](https://github.com/JustAnotherArchivist/snscrape) to scrape all publicly posted tweets using both the words _todos_ and _todes_ between October 2019 and July 2021. Additionally, I also scraped all tweets ever using _todes_ in Santiago de Chile.  

### Analysis

The analysis is splitted into two sections. 

First, I compare the use of _todes_ vs _todos_, observing that the use of _todes_ is still marginal compared to the use of _todos_. However, when analysing the use of _todes_ by itself, it is possible to appreciate that its use has been explosive, and that it big leaps in usage growth are connected to political events that foster its acceptance. 

![Growth of use of _todes_ in Tweets in Santiago de Chile](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/images/Screenshot%202021-07-29%20at%2018.18.26.png?raw=true)

Secondly, I tokenized the content of the tweets using _todes_ to analyse it using the [NLTK toolkit](https://www.nltk.org/). It is possible to observe that its use is very political, specially when doing sentiment analysis, using [sentiment-Spanish](https://pypi.org/project/sentiment-analysis-spanish/), that classifies most tweets as negative, even though the intention behind the authors may not, but because the language they use signals a very political motif. 

![_Todes_ tweets sentiment classification](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/images/Screenshot%202021-07-29%20at%2021.56.14.png?raw=true)

#### Links

+ [Web scrapping code](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/code/Inclusive_language_project.ipynb)
+ [_Todes_ analysis code](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/code/todes.ipynb)
+ [All tweets database](https://github.com/pedropabloerr/use_of_todes_in_chile/blob/main/databases/todestodoslimpio.csv.zip)
+ [Todes tweets database](https://github.com/pedropabloerr/use_of_todes_in_chile/tree/main/databases#:~:text=.%E2%80%8A.-,todes2.csv,-final)
+ [Presentation including visualizations (pdf)](https://github.com/pedropabloerr/use_of_todes_in_chile/tree/main/presentation#:~:text=.%E2%80%8A.-,Presentation.pdf,-final)
+ [Visualizations in Tableau Public](https://public.tableau.com/views/proyecto_todes/Sheet13?:language=es-ES&:display_count=n&:origin=viz_share_link)
