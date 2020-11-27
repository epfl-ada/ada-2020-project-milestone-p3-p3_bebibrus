# ada-2020-project-milestone-p3-p3_bebibrus

**Title**

Effect of different matching methods on the paper conclusions 


**Abstract**

“Housing,  Health, and Happiness” is an extremely interesting paper which demonstrates that simple housing improvements in slum areas are beneficial for child health and cognitive development as well as adult happiness. If this is indeed true, the paper should be a source of inspiration for governments taking action to combat poverty. However, this pleasing conclusion is drawn from an observational study and may thus be biased by confounders. 
For this reason, we decided to see if we obtain the same conclusion after having properly balanced the control and treatment group using adequate matching methods. To do so, we are going to use the same dataset and the same statistical methods (linear regressions) as the paper, but extra efforts will be made to find the best matching between the control and treatment groups.



**Research Questions**

Are the results obtained in the paper dependent on the matching technics used?
Can we find an optimal matching method? 
With this optimal method, do we get the same conclusions as the paper ? 


**Proposed dataset**

As mentioned before, we are using the same datasets as the paper. It contains a dataset with information at the household level, including data from both the 2000 Mexican Census and the 2005 Survey. It also contains a dataset with information at the individual level, including data from the 2005 Survey. We have 2,755 samples for our analysis. 


**Methods**

When dealing with observational studies, care should be taken before drawing causal conclusions about the effect of a treatment on a population. Indeed, confounding effects may be present and these have to be eliminated. A common way to achieve this is to use matching methods. Several matching methods exist such as nearest neighbor matching, subclassification, full matching or Weighting. And all of these can be used with different distance measures such as Mahalanobis or propensity score distances. Once the treatment group and the control group are matched, it is necessary to assess the covariate balance between these two groups (similarity of the empirical distributions of the full set of covariates). If the two groups are not well balanced, another matching method or distance measure should be used. For the project, we will find the matching method and the distance measure which balance the covariates as best as possible. We will then see if the conclusions of the paper are still valid. \
**Reference:** Stuart EA. Matching methods for causal inference: A review and a look forward. Stat Sci Rev J Inst Math Stat. 2010;25(1):1-21. doi:10.1214/09-STS313


**Proposed timeline**

- 04/12 choose one distance measure and one matching method for each team member
- 07/12 Make the matching and analyse covariate balance  
- 08/12 Compare methods and select the best matching 
- 13/12 Make the replication of tables with the best matching 
- 15/12 Clear code, add explanations  


**Organization within the team**

Each team member will choose one matching method as well as one distance measure and will do the following:
- Calculate the distances
- Match the groups according to the chosen method 
- Calculate covariate balance between the two groups \

We will finally compare our results to find the distance measure and the matching method that best balance the groups. With this optimal balance, we will see if the paper conclusions are still valid .
 
**Questions for TAs (optional)**

- Is it more reasonable to check the conclusions related to a few Tables (i.e. Table 4 and 5) or related to all Tables ?

- Is it better to check the conclusions for each matching method we are going to test or just for the optimal one ? 
