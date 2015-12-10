# Diabetes-Tri-Study
Coordinated data analysis exploring relationship between diabetes and cognitive decline moderated by cardiovascular risk factors 

**Keywords:**: Hypertension; diabetes mellitus; episodic memory; cognitive aging; coordinated analysis

# Graphs for examination
To provide the reader with a convenient access to the statistical graphics of the current project all plots have been organized into meaningful collections, reports.  


- [Diabetes-Tri-Study](Diabetes-Tri-Study.md) show the essential information about data and models. The report shows histograms of frequency counts and spaghetti plots of individual trajectories. Observed and expected trajectories are shown for each study. Although TIME IN STUDY was entered as a predictor, each model is supplemented by a view of the expected trajectories with BIOLOGICAL AGA on the x-axis.
- [Compare Studies](Compare_Studies.md) reports the main effects and the effects of the four co-morbid conditions on cognitive function across studies. Specific effects for each study are reported as well.

- [Fi1 & Fig2](Fig1and2.md) modifies color graphs from [Compare Studies](Compare_Studies.md) to agree with journal requirements  
- [Basic Graphs](BasicGraphs.md) shows reconstructed individual trajectories and marks the expected trajectory for each co-morbid combination (No diabetes & no hypertension, diabetes & no hypertension, no diabetes & hypertension, and  diabetes & hypertension). modifies color graph from [Diabetes-Tri-Study](Diabetes-Tri-Study.md) to fit publication format.

- [FE vs FS](yHat-vs-yCond.md) is a sidetracking investigation. It compare individual trajectories recostructed from the estimated fixed effect(FE) and expected trajectories reconstructed from factor scores(FS) reported by MPLUS.

- if you would like to review the reports in an interactive HTML version please [download and unzip the archived file](), then open individual .html files or browse .png in a image viewer.

## Abstract  
The importance of preventing and controlling both **hypertension** (HTN) and **diabetes** mellitus (DM) to mitigate risks to physical health has long been understood by healthcare professionals. More recently, a growing body of evidence also implicates HTN and DM in age-related **cognitive decline** and risk for dementia, though consensus has yet to be reached on which cognitive domains are most vulnerable or whether older adults living with comorbid HTN and DM are at heightened risk for cognitive impairment. The present study sought to bring synthesis to this topic through the **coordinated analysis** of three longitudinal studies of aging. Identical multilevel linear growth models were fit to each study to estimate the impact of baseline disease status on verbal **episodic memory** level and change in late-life. Our findings suggest that independent and comorbid HTN and DM are differentially associated with verbal **episodic memory** and that these associations are context-dependent. The direction of estimates for the association between independent HTN and change in performance were mixed across studies. In only one study were independent DM and comorbid HTN and DM significantly related to performance. Given this, we recommend that future work explicitly differentiate between individuals diagnosed with HTN and/or DM through exclusion or model adjustment to avoid introducing confounds to results. Future coordinated analyses will help to disentangle the impacts of various social and contextual factors on the relation between **cardiovascular disease risk factors** and changes in **cognitive functioning**.


## Documentation

- this [vignette](http://cran.r-project.org/web/packages/MplusAutomation/vignettes/Vignette.pdf) demonstrates the use of  [MplusAutomation](http://cran.r-project.org/web/packages/MplusAutomation/MplusAutomation.pdf) package used in this project to process the statistical models. 

## Link

 - [yHat-vs-yCond](yHat-vs-yCond.md)