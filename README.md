# Meta-analyses-Word-Production

In cognitive psychology/experimental psychology, we often rely on experimental data to test our theories. Meta-analyses provide a summary of the empirical evidence available at a given point in time on a given effect. They are incredibly useful because they quantify the evidence on which we can build our next studies and theories. They provide an idea of the size of an effect (how bit ig is) and of its precision. This can be used to run power analyses (analyses that help decide how many participants are needed to find an effect in a future experiment) and build more precise computational models.

In the last few years (starting during the pandemic, when it was difficult at first to collect new experimental data) we conducted Bayesian meta-analyses of several experimental effects in language production research. In addition, having access to raw datasets, we were able to test novel hypotheses about these effects. Here are a few examples:



## Syllable frequency effect (or why we are faster at saying _bri_ than _blo_?)
Words made of frequent syllables can be prepared faster for production than words made of low frequency syllables. THis effect has been used to constraint models of word production and in particular, to argue that syllables are stored in the long term memory of the speaker. The figure below shows the results of a meta-analysis of this effect. This is a posterior distribution: it shows the most likely value of this effect (difference, in milliseconds between words with low and words with high syllable frequencies) as well as other possible values and their probabilities.

<br>

<p align="center">

<img src="./Post_Distr_an1.png">
 
<br>

We see that most values are positive but also that this is a very small effect. 
The code and data to reproduce this analysis can be accessed [here](https://osf.io/4nmbj/)


<br>
  
## Effects of distractors (or why we are faster at saying "Spider" with the word "Boat" on top than with the word "Ant"?)
The picture-word paradigm is variant of the [stroop paradigm](https://www.psytoolkit.org/experiment-library/stroop.html). Participants name a picture and have to ignore a written word on presented with the picture, as in the picture below. 
 
<br>

 
<img src="./038_Spinne_SemRelated.png">
 

<br>

The overall picture seems to be that
- Many of the effects reported early on are real. 
- Evidence on moderators of these effects, which is crucial to disantangle existing theories of these effects, is often lacking. 
  
  
<br>

## References, with links to data and code

Bürki, A. van den Hoven, E., Schiller, N.O., & Dimitrov, N. (submitted). Cross-linguistic differences in gender congruency effects: Evidence from meta-analyses. [pre-print](https://arxiv.org/abs/2109.03490)  

Bürki, A., Alario, X., & Vasishth, S. (2022). When words collide: Bayesian meta-analyses of distractor and target properties in the picture-word interference paradigm. _**The Quarterly Journal of Experimental Psychology**_. ([data & scripts](https://osf.io/sjn5b/)) ([pre-print](https://arxiv.org/abs/2008.03972))
  
Fuhrmeister, P., & Bürki, A. (2022). Distributional properties of semantic interference in picture naming: Bayesian meta-analyses.  _**Psychonomic Bulletin & Review**_, 29(2):635-647. doi: 10.3758/s13423-021-02016-6. 
([data & scripts](https://osf.io/v2fx5/)) ([paper](https://link.springer.com/article/10.3758/s13423-021-02016-6))
  
Bürki, A., Elbuy, S., Madec, S., & Vasishth, S. (2020). What did we learn from forty years of research on semantic interference? A Bayesian meta-analysis. _**Journal of Memory and Language.**_ ([paper](https://www.sciencedirect.com/science/article/pii/S0749596X20300395)) ([data & scripts](https://osf.io/k6f4c/)) doi:10.1016/j.jml.2020.104125

 
  



 




