# Predicting a Car's Time to Sell

_Winning project in the University of Manchester MathSoc x AutoTrader Hackathon, March 2024_

!(A collection of feature plots)[https://github.com/tcassar/autotrader-predictions/blob/main/img/feature-plots.png]

---
## The Brief

Our task was to predict how long it would take a car listed on AutoTrader's platform to sell. With a tight deadline of 10 days, and 250,000 rows of data, we aimed to build a model to answer this question quickly and accurately on unseen cars. 

Who are we?
* Ioan Gwenter ([www.linkedin.com/in/ioan-gwenter](https://www.linkedin.com/in/ioan-gwenter/), [www.github.com/ioan-gwenter](https://github.com/ioan-gwenter))
* Lourenço Silva ([www.linkedin.com/in/lourencofsilva](https://www.linkedin.com/in/lourencofsilva/), [www.github.com/lourencofsilva](https://github.com/lourencofsilva))
* Tom Cassar ([linkedin.com/in/tom-cassar](https://linkedin.com/in/tom-cassar), [www.github.com/tcassar](https://github.com/tcassar))

---
## Our Approach

We studied the machine learning pipeline, and immediately built a model that worked brilliantly - however, we had a problem with data leakage. So, we restarted and did some in-depth data exploration (see [`./exploration`](https://github.com/tcassar/autotrader-predictions/tree/main/exploration)). 

We experimented with decision trees, random forests, and artificial neural networks [`./models`](https://github.com/tcassar/autotrader-predictions/tree/main/models). We looked at published papers to see if regression or classification would be a better approach. We tried automated ML platforms such as [Edge Impulse](https://edgeimpulse.com/), and [FeatureTools](https://www.featuretools.com/) - an automated feature engineering platform. We looked at various forms of hyper-parameter optimisation and model evaluation. 

---
## Achievements

Selected to showcase our work, we presented our findings to AutoTrader and fellow finalists. The presentation, complete with slides and speaker notes, is available in [`./slides`](https://github.com/tcassar/autotrader-predictions/tree/main/slides).

It was extremely interesting to see the approaches that the other teams had taken. Everyone had a different approach to feature engineering that came with their own positives and negatives.
