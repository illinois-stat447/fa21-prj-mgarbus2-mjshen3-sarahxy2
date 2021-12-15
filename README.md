# fa21-prj-mgarbus2-mjshen3-sarahxy2

This version of the repo is a clone of the original repo except with the data removed and therefore the also the git history removed. The data is available on request from the [NSRR](https://sleepdata.org/about).

## Learning to Rest: Predicting Sleep from Fitness

As college students who sometimes have to prioritize other things over exercise, sleep, or both, we are interested in how fitness can affect the quality of sleep. We were able to get datasets from the Stanford Technology Analytics and Genomics in Sleep [(STAGES)](https://pubmed.ncbi.nlm.nih.gov/29860441) study which contains collected data on over 1,500 anonymized adult or adolescent patients evaluated for sleep disorders thanks to the  [The National Sleep Research Resource](https://sleepdata.org/about). The STAGES data contained sleep polysomnography recordings (where in electrodes are attached to the body to record sleep data — the gold standard for sleep studies), surveys done on the participants before the study, and surveys done on the participants after the study. The surveys contained fitness data and past health data which we used to determine people who were fit, and people who were good sleepers. We used this data to determine if we could predict a good sleeper from their fitness attributes using 3 machine learning techniques: XGBoost, KNN, and Elastic-Net.

## Project Report
The project report can be found in pdf format as `Project.pdf` and in Rmarkdown as `Project.Rmd` in the repo. 

## Link to presentation: 
[Click here for our presentation!](https://uofi.app.box.com/s/o75fwn3e5ggr11dj7b8ar6t1mqpkztzu)

We recorded our presentation before realizing that it should be submitted in Rmarkdown. We were able to write an exact copy of the presentation we used in our video, save for some slides continuing for longer due to spacing issues.

The slides used for our presentation can be found hosted on the Google slides website [here](https://docs.google.com/presentation/d/1-0BLSHjEyIH5pQ8I9knKbSynBglYiARw9JxzA-hjnmA/edit?usp=sharing), or on Box [here](https://uofi.box.com/s/sbetg1tpxotyijwgclg37d067beob9im). The Rmd and HTML files for the slides exist as `presentation.Rmd` and  `presentation.html` on this repo. A shortened, more compact version exists as `lightning_presentation.Rmd` and `lightning_presentaiton.html`
