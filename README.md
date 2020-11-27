# ada-2020-project-milestone-p3-p3_bebibrus

Title

Testing different matching methods


Abstract

“Housing,  Health, and Happiness” is an extremely interesting paper which demonstrates that simple housing improvements in slum areas are beneficial for child health and cognitive development as well as adult happiness. If this is true, the paper should be a source of inspiration for governments taking action to combat poverty. However, this pleasing conclusion is drawn from an observational study and may thus be biased by confounders. 
For this reason, we decided to see if we obtain the same conclusion after having properly balanced the control and treatment group using adequate matching methods. To do so, we are going to use the same dataset and the same statistical methods as the paper, but extra efforts will be made to find the best matching between the control and treatment groups.



Research Questions

Is there a better matching method to use? 
Are the results obtained in the paper dependent of the matching technics used?
Are the conclusions made the same? 


Proposed dataset

As mentioned before, we are using the same dataset as in the paper. It contains a dataset with information at the household level, including data from both the 2000 Mexican Census and the 2005 Survey. It also contains the dataset with information at the individual level, including data from the 2005 Survey.  We have 2,755 samples for our analysis. 


Methods

When dealing with observational studies, care should be taken before drawing causal conclusions about the effect of a treatment on a population. Indeed, confounding effects may be present and these have to be eliminated. A common way to achieve this is to use matching methods. Several matching methods exist such as nearest neighbor matching, subclassification, full matching or Weighting. And all of these can be used with different distance measures such as Mahalanobis or propensity score distances. Once the treatment group and the control group are matched, it is necessary to assess the covariate balance between these two groups (similarity of the empirical distributions of the full set of covariates). If the two groups are not well balanced, another matching method or distance measure should be used. For the project, we will find the matching method and the distance measure which balance the covariates as best as possible. We will then see if the conclusions of the paper are still valid.


Proposed timeline

- 04/12 Find propensity scores 
- 07/12 Find best matching 
- 08/12 Determine if the two groups with this matching are well balanced 
- 13/12 Do the replication of tables with the new matching 
- 15/12 Clear code, add explanations 


Organization within the team

Each team member will choose one of the matching methods and we will do the following:
- Calculate propensity score
- Find best matching with it
- Calculate covariate balance between these two groups
- Replicate tables of the paper
We will finally compare the results and see if we come to the same conclusions as the ones in the paper.


Questions for TAs (optional)
