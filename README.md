# Meta-analyses-Word-Production

In cognitive psychology/experimental psychology, we often rely on experimental data to test our theories. Meta-analyses provide a summary of the empirical evidence available at a given point in time on a given effect. They are incredibly useful because they quantify the evidence on which we can build our next studies and theories. They provide an idea of the size of an effect (how bit ig is) and of its precision. This can be used to run power analyses (analyses that help decide how many participants are needed to find an effect in a future experiment) and build more precise computational models.

In the last few years (starting during the pandemic, when it was difficult at first to collect new experimental data) we conducted Bayesian meta-analyses of several experimental effects in language production research. In addition, having access to raw datasets, we were able to test novel hypotheses about these effects.



## Syllable frequency effect (or why we are faster at saying _bri_ than _blo_?)
Words made of frequent syllables can be prepared faster for production than words made of low frequency syllables. THis effect has been used to argue that syllables are stored in the long ter
m memory of the speaker. We conducted a meta-analysis of this effect. The figure below shows the results of this analysis. This is a posterior distribution, it shows the most likely value of this effect (difference, in milliseconds between words with low and words with high syllable frequencies). 

<p align="center">

<img src="https://user-images.githubusercontent.com/28299451/225906578-e96c4aab-ccb4-40df-971b-f1d040d3beba.png" width=50% height=50%>
 
 
<br>

We see that most values are positive but also that this is a very small effect. The code and data to reproduce this analysis can be accessed [here](https://osf.io/4nmbj/)


<br>
  
## Effects of distractors (or why we are faster at saying "Spider" with the word "Boat" on top than with the word "Ant"?)
In this project we performed meta-analyses of several effects that are often cited and have been used to build or constrain theories of word production processes. Many of these effects were obtained with a variant of the stroop paradigm (i.e., name the color you see and ignore the name of a different color written on top). In this paradigm, participants name a picture and have to ignore a written word on the picture, as in the picture below.

 
<img src="https://user-images.githubusercontent.com/28299451/225906728-f287904a-4aea-4ac5-993e-669d44c96686.png" width=30% height=30%>
 
 
 
The overall picture seems to be that
- Many of the effects reported early on are real. 
- Evidence on moderators of these effects, which is crucial to disantangle existing theories of these effects, is often lacking. 
  
  

## References, with links to data and code

Bürki, A. van den Hoven, E., Schiller, N.O., & Dimitrov, N. (submitted). Cross-linguistic differences in gender congruency effects: Evidence from meta-analyses. [pre-print](https://arxiv.org/abs/2109.03490)  

Bürki, A., Alario, X., & Vasishth, S. (2022). When words collide: Bayesian meta-analyses of distractor and target properties in the picture-word interference paradigm. _**The Quarterly Journal of Experimental Psychology**_. ([data & scripts](https://osf.io/sjn5b/)) ([pre-print](https://arxiv.org/abs/2008.03972))
  
Fuhrmeister, P., & Bürki, A. (2022). Distributional properties of semantic interference in picture naming: Bayesian meta-analyses.  _**Psychonomic Bulletin & Review**_, 29(2):635-647. doi: 10.3758/s13423-021-02016-6. 
([data & scripts](https://osf.io/v2fx5/)) ([paper](https://link.springer.com/article/10.3758/s13423-021-02016-6))
  
Bürki, A., Elbuy, S., Madec, S., & Vasishth, S. (2020). What did we learn from forty years of research on semantic interference? A Bayesian meta-analysis. _**Journal of Memory and Language.**_ ([paper](https://www.sciencedirect.com/science/article/pii/S0749596X20300395)) ([data & scripts](https://osf.io/k6f4c/)) doi:10.1016/j.jml.2020.104125

 
  



 




