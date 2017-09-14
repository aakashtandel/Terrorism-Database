# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 5: Predicting Terrorism with Bayesian Inference

## Overview
The objective of this project was to gain an understanding of terrorism using Bayesian inference. My analysis specifically looked at the Phillippines in Southeast Asia. My working knowledge on terrorism in Southeast Asia was limited. But this line of inquiry was sparked by the chaotic situation in Marawi City, Philippines where Philippine Government security forces fought (and continue to fight depending on when this is read) ISIS affiliated militants known as Abu Sayyaf and Maute. 

I utilized the Global Terrorism Database which contained over 170,000 cases of terrorism from around the globe. The National Consortium for the Study of Terrorism and Responses to Terrorism (START) maintains this database. START is headquartered at the University of Maryland. At the time of the submission of this project, terror attacks from 1970 to 2016 were accounted for. The database contained over one hundred and thirty variables including geographic location, type of attack, perpetrators, targets, outcomes, number of fatalities, and motivation of perpetrators. This was a very robust dataset but it did contain a fair amount of missing information. In particular, 1993 data was lost. One additional goal of this analysis was to impute the number of bombings that occurred in 1993.

The full breakdown of the Markov Chain Monte Carlo method can be found in the Jupyter Notebook associated with this project. The MCMC method revealed there was a statistical difference between pre-2010 bombings in the Philippines and post-2010 bombings. The credible intervals between the two groups did not overlap and the difference in means was statistically different than zero. Overall, this analysis isn’t very surprising because of the global trend in increased terrorism starting in the early 2000’s. An industry expert with prior knowledge of terrorism could more readily utilize MCMC methods in order to derive key insights into the world of terrorism analysis.

It seems that the number of terror bombings has increased across the globe since 2010 and increased markedly in the Philippines. Overall, it is with the help of START that we can learn more about terrorist activities and develop proper strategies in order to counteract their threat.

## About the Dataset

From Kaggle:
> The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2015 (with annual updates planned for the future). The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 150,000 cases. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the [University of Maryland](http://start.umd.edu/gtd/).

> Geography: Worldwide

> Time period: 1970-2015, except 1993 (2016 in progress, publication expected June 2017)

> Unit of analysis: Attack

> Variables: >100 variables on location, tactics, perpetrators, targets, and outcomes

> Sources: Unclassified media articles (Note: Please interpret changes over time with caution. Global patterns are driven by diverse trends in particular regions, and data collection is influenced by fluctuations in access to media coverage over both time and place.)

> Definition of terrorism:

> "The threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation."


## Materials 
- Jupyter Notebook: "Project 5 - Predicting Terrorism with Bayesian Inference.ipynb"
- Presentation: "Global Terrorism Database Project.pdf"
- Executive Summary: "Executive Summary Global Terrorism Project.pdf"
