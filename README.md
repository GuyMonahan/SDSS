

# Sloan Digital Sky Survey (SDSS) for Mapping the Cosmos


<p align="center">
 <img width="800" height="500" src=images/SDSS.jpg>
 </p>

## Outline:
* Scientific Proposal
* Our Approach
* Model
* Conclusion 

__________________________________________

* Scientific Proposal:

Exploring the cosmos has taken a new turn for the better of humanity. Astrophysicists have become the new Lewis and Clark for mapping the most detailed three dimensional map of our cosmos that is 100 times larger than any previous known map. Understanding the cosmos and the exact position of celestial objects give future explorers insight into how matter is dispersed among the known universe, as well as how future explorers will want to traverse local celestial objects in the search for our next habitable planet for all of humanity. By differentiating between three distinct classes of stars, galaxies, and quasars future travelers can know exactly what celestial objects to investigate for humanity to keep thriving among the cosmic sea. 

* Our approach:

In determining our three classifications of whether the object that SDSS has imaged comes from several key features from the SDSS DR 14 dataset from kaggle. This dataset consists of 10,000 known observations each having a photometric spectrum that spans the ultraviolet (uv), green (g), red (r), infrared (i), and near-infrared (ni) bands, along with their apparent redshift. Under previous scientific research, it is concluded that quasars have the largest redshift as they are black holes with jets pouring out of the poles from incoming material from the accretion disk, making for a distinct classification when using algorithmic models in prediction of the three definitive classes as seen in figure 1. This main issue comes with the classification of galaxies and quasars, as a portion of quasars have a redshift that is similar to galaxies that are equivalent to the recession in respect to Earth. Our team deals with this issue by utilizing the band filters where the quasar peaks in the near-infrared to infrared bands due to the large recession that is occurring. Galaxies that are amongst the homogenous type show a peak in green to red bands that are distinctive from quasars peaks. Stars being the class the easiest class to classify due to the low redshift that occurs in comparison to galaxies and quasars.


<p align="center">
 <img width="750" height="350" src=images/ps.png>
 </p>



<p align="center">
 <img width="800" height="300" src=images/redshift.png>
 </p>

* Model

Under the many classification models that could have been utilized, the best model that we chose was using random forest. Random forest allows for additional randomness in comparison to decision trees. The most crucial aspect of random forest is that it decides on the best feature in a random subset of features rather than the most important feature to split on allowing a wider diversity of features than simply just the best feature to choose upon. Another aspect of random forest is that it has a lower risk of overfitting in comparison to decision trees, while random forest does have the drawback of being biased with categorical variables. 


* Conclusion 

In conclusion, random forest gives us the best model to predict whether our celestial object that we are identifying among the interstellar medium. When humanity is trying to travel to far reaches of our galaxy, and beyond, knowing the galactic map will prove worthy in having to make sure the survival of humanity goes forth with aptitude in finding the next home for human beings to keep thriving. If we choose to use a model like decision trees in comparison to random forest for prediction, our error of prediction of stars is 0.0055%, which seems negligible but can have great cost when the distances among celestial objects are in the terms of light years. Being off just a mere distance of a light year can cost a colony years, in turn, meaning the loss of humanity forever. 
