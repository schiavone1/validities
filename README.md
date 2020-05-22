# The Four Validities: A Short Guide for Reviewers in Social & Personality Psychology

Simine Vazire & Sarah Schiavone 

## Construct Validity
Construct validity refers to whether the study actually measured and/or manipulated the constructs that the authors wished to study. Construct validity includes the conceptual MATCH between the construct(s) and the operationalization(s) made, and also the QUALITY of the measure/manipulation. If the match is poor, construct validity is poor regardless of the quality of the measures.  

### Common potential threats to construct validity:
#### Match
* Poorly defined construct(s)   
* Poor face validity (i.e., it does not appear to measure what it claims to measure). 
    * Measures/manipulates something other than (or in addition to) the construct of interest.  
    * Measures/manipulates only a narrow part of the construct of interest.  
* Poor method match – e.g., using a self-report to measure a behavior, or using physiology to measure a subjective feeling, etc.   

#### Quality
#####  *Measures*
* Measures are not validated (most ad hoc measures are not validated – reporting reliability is not enough)
* Scoring of the measure (into one overall score or multiple subscale scores) ignores theoretical or empirical considerations about factor structure of the concept or measure
* Biased or confusing language in questionnaire items
* One-shot behavioral measures (usually a dependent variable like donating your participant payment to charity or administering hot sauce to another participant)
* Single vignette/stimulus
* Method-specific variance (e.g., variance due to using only self-reports) contaminating the measurement of the construct – this is very common and often not considered a big threat, but often there is reason to worry about bias introduced by the method.
* The way the measure is administered (e.g., lack of privacy) could introduce bias 

#####  *Manipulations*
* Manipulation is not validated (a manipulation check can provide some evidence of validity but is often impractical or impossible; ideal is independent validation in separate studies)
* Manipulation is too subtle, not likely to actually induce the intended state
* Manipulation is confounded, likely manipulating something else or something broader than the intended state (e.g., “remember a time when” manipulations are often at high risk for confounds because memories that vary on the manipulated characteristic (e.g., status/power) likely also vary systematically on other characteristics (e.g., age at the time of remembered event)).


## Statistical Validity (or Statistical Conclusion Validity)

Statistical validity refers to the validity of statistical inferences, putting aside any concerns about measurement, conceptual rigor, etc. Inferential statistics require certain assumptions to be met. For example, frequentist statistics (e.g., *p*-values, confidence intervals) aim to control error rates and are only valid when decisions about data collection and analysis are made a priori, and are not data-dependent. Thus, flexibility in how data are collected or analyzed can pose a serious threat to the validity of many statistical inferences. It is not always obvious whether such flexibility was present (except when the authors share a pre-registered plan). However, there are often signs of flexibility.  

There are many other kinds of statistical errors or problems, too.  

To evaluate statistical validity, consider whether the authors conducted a strong and appropriate statistical test of their research question, and interpreted the results of the statistical test correctly.

### Common potential threats to statistical validity:
* *p*-hacking, which can take many forms. Some potential clues include but are not limited to:
    * Flexible analysis decisions (e.g., removing outliers or otherwise excluding some participants or observations, adding covariates, dropping items from measures, transforming variables, etc.), particularly when alternative decisions would also have been reasonable
    * *p*-values between .01 and .05, especially across multiple studies (when the effect is real, unbiased statistical tests would produce a heavily-skewed distribution of *p*-values, with most *p*-values below .01)
    * Conducting many statistical tests (e.g., testing three separate DVs) but failing to correct for family wise error rates / multiple comparisons
    * Conducting many statistical tests (e.g., testing three separate DVs) but failing to correct for family wise error rates / multiple comparisons
    * Optional stopping – not clear what the data collection stopping rule was.  (Inconsistent or strange sample sizes could be a clue.). 
* HARKing (Hypothesizing After the Results are Known)
    *  When there is no significant effect overall, changing the focus to a subgroup where the effect is significant (e.g., “it works for women”)
    * Changes across studies in direction of the effect, or in the specific pattern observed, still interpreted as consistent with theory despite a lack of theoretical justification
* Low statistical power or precision (small sample size/number of observations)
* Interpreting a result as evidence of “no difference” or “no effect” based just on a non-significant p-value (without actually testing for evidence of absence, e.g., using equivalence testing or Bayesian stats). This often happens for non-central hypothesis tests, like ruling out potential confounds or alternative explanations.
* Not actually testing the effect of interest (e.g., reporting that two effects are different from each other because one is statistically significant and the other isn’t, rather than testing the interaction directly)
* Floor or ceiling effects, or other restriction of range problems 
* Outliers driving the effect or exaggerating the size of the effect
* Using the wrong statistical technique (e.g., doing a median split on a continuous variable) 
* Failing to meet important assumptions of statistical tests (e.g., ignoring interdependence or clustering in data, e.g., analyzing groups or couples as individuals)
* Threats to measurement invariance – if there is a reason to worry that the same measure could have different meaning in different groups or at different times
* Complicated effects like moderated mediation, causal models with many links/paths, or higher order interactions (even a 2-way interaction can be reason for skepticism, but especially 3-way or higher) without cross-validation or direct replication - these are susceptible to overfitting or spurious effects
* A significant interaction but the effect is driven by a pattern different from what the theory predicts (e.g., if the theory would say that cell A1 should be lower than cells A2, B1, and B2, but the pattern of results does not look like that)
* Claiming implausibly large effect sizes, or otherwise too-perfect data (e.g., means are perfectly equally spaced apart, distributions barely overlap, etc.)
* Claiming evidence for an effect with a *p*-value larger than .05, or being inconsistent in the application of the *p*-value threshold (i.e., playing fast and loose with alpha) 
* Controlling for variables that were measured with error, without using latent variables or otherwise taking the error into account


## Internal Validity

Internal validity refers to whether claims about causal relationships among variables are warranted by the evidence. To assess internal validity, compare the authors’ claims about causal relationships (if any) with what the design of the study could reasonably allow with respect to causal claims. Sometimes claims about causality are implied rather than stated explicitly.

### Common potential threats to internal validity:

#### In the context of experimental designs:
* Confounds that are part of the manipulation - the manipulation likely affected other variables besides the independent variable (this is also a threat to the construct validity of the manipulation)
* Confounds outside of the manipulation - other things were different between conditions besides the manipulation 
* Poor/weak manipulation - manipulation is too subtle or likely doesn’t have much effect on the independent variable 
* No true control condition, or the control condition was not similar enough to the experimental condition (did not have exactly the same experience as the experimental condition, besides the manipulated variable)
* Demand effects - participants are responding to what they think they are supposed to say/do or what they think the experimenter wants them to say/do (may be especially likely in within-subjects designs, but can also happen in between-subjects designs)
* Non-random assignment to conditions 
* Having lots of participants who drop out after the manipulation (messes up random assignment)
* Incorrect use and/or interpretation of mediation analyses

#### In the context of correlational/observational designs:
* Ignoring possible third variables (e.g., selection effects, confounds) 
* Ignoring possible reverse causality
* Making unwarranted assumptions to rule out alternative explanations 
* Controlling for things that shouldn’t be controlled for (e.g., a potential mediator or collider) or throwing in a bunch of controls that seem haphazard
* Controlling for variables that were measured with error, without using latent variables or otherwise taking the error into account
* Regression to the mean (if participants were selected based on extreme scores)
* Incorrect use and/or interpretation of mediation analyses

## External Validity

External validity refers to the validity of generalizations made from the data. This includes generalizations made to other people, other times, other settings (e.g., lab to real world), other stimuli, other measures or manipulations, and other ways of testing the same research question (including everything from other experimenters to other recruitment strategies and more). Few studies can fully justify these kinds of generalizations, but many do make such claims, implicitly or explicitly.  How much did the authors state or imply that their results would generalize beyond factors that they actually tested?  

### Common potential threats to external validity:
* Claiming that an effect generalizes to a population of participants, measures/manipulations, or settings not sampled in the study, particularly if there is reason to doubt the plausibility of this claim
    * Note that it can even be risky to claim that the effect applies to a specific subset of participants, measures/manipulations, or settings that were sampled, if the authors did not directly test whether the effect holds in that specific subset of the data (e.g., making claims about an effect being true for older adults when the sample and analyses include both younger and older adults and no the authors did not test if the effect holds across age groups).  
* Examining only a narrow slice of the construct of interest (e.g, using a single or just a couple stimuli or vignettes).
* Contrived lab setting or lack of realism (e.g., using a hypothetical scenario instead of a real situation; or reducing a complex experience like trauma to a trivial manipulation like getting a crappy prize).
* Recruiting participants from an inappropriate population (e.g., sampling only college students when studying a phenomenon like workplace misconduct that is likely to vary a lot by age/experience).
* Making claims based on data from a convenience sample that would require a representative sample (e.g., claims about frequency or absolute levels of a single variable (e.g., “80% of women have experienced discrimination”) require a representative sample)


#### Acknowledgements: 
This document is inspired by Shadish, Cook, & Campbell (2002) Experimental and Quasi-Experimental Designs for Generalized Causal Inference, and Morling (2017) Research Methods in Psychology.  I am grateful to our research group at UC Davis, Daniël Lakens, Fiona Fidler, and Eden Smith, for feedback.  All errors and stupidities are ours.  
