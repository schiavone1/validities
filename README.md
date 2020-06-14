# The Four Validities: A Short Guide for Reviewers in Social & Personality Psychology

Simine Vazire & Sarah Schiavone 

## Construct Validity
Construct validity refers to whether the study actually measured and/or manipulated the constructs that the authors wished to study. Construct validity includes the conceptual **_match_** between the construct(s) and the operationalization(s) made, and the **_quality_** of the measure(s)/manipulation(s). If the match is poor, construct validity is poor regardless of the quality of the measures.  

### Common potential threats to construct validity:
#### Match
* **C1.** Poorly defined constructs (e.g., inconsistent and/or unclear operationalization, conceptually fuzzy). 
* **C2.** Poor face validity (i.e., it does not appear to measure what it claims to measure).
   * Measures/manipulates something other than&mdash;or in addition to&mdash;the construct of interest.
   * Measures/manipulates only a narrow part of the construct of interest.
* **C3.** Poor method match (e.g., self-reports used to measure behavior, physiological methods used to measure subjective feelings). 

#### Quality
#####  *Measures*
* **C4.** Measures are not validated. Most ad hoc measures are not validated&mdash;reporting reliability is not enough.
* **C5.** Measures are scored in ways that ignore theoretical or empirical considerations about the factor structure of the construct(s).
* **C6.** Measures include biased and/or confusing language.
* **C7.** Relying on a single vignette/stimulus.
* **C8.** Relying on one-shot behavioral measures (usually a dependent variable like donating your participant payment to charity or administering hot sauce to another participant).
* **C9.** Measures are contaminated by method-specific variance (e.g., variance due to using only self-reports)&mdash;this is very common and usually not considered a serious threat, but often there is reason to worry about bias introduced by the method.
* **C10.** Measures administered in ways that could introduce bias (e.g., lack of privacy).

#####  *Manipulations*
* **C11.** Manipulations are not validated (manipulation checks may provide some evidence of validity but are often impractical or impossible; ideally, independent validation occurs in separate studies).
* **C12.** Manipulations are too subtle, unlikely to actually induce the intended state.
* **C13.** Manipulations are confounded, likely manipulating something else or something broader than the intended state (e.g., “remember a time when” manipulations are often at high risk for confounds because memories that vary on the manipulated characteristic (e.g., status/power) likely also vary systematically on other characteristics (e.g., age at the time of remembered event)).

## Statistical Validity (or Statistical Conclusion Validity)

Statistical validity refers to the validity of statistical inferences, putting aside any concerns about measurement, conceptual rigor, etc. Inferential statistics require certain assumptions to be met. For example, frequentist statistics (e.g., *p*-values, confidence intervals) aim to control error rates and are only valid when decisions about data collection and analysis are made a priori, and are not data-dependent. Thus, flexibility in how data are collected and analyzed can pose a serious threat to the validity of many statistical inferences. It is not always obvious whether such flexibility was present (except when the authors share a pre-registered plan). However, there are often signs of flexibility. There are many other kinds of statistical errors or problems, too.  

To evaluate statistical validity, consider whether the authors conducted a strong and appropriate statistical test of their research question, and interpreted the results of the statistical test correctly.

### Common potential threats to statistical validity:
* **S1.** *p*-hacking, which can take many forms. Some potential clues include but are not limited to:
   *	Flexible analysis decisions (e.g., removing outliers or otherwise excluding some participants or observations, adding covariates, dropping items from measures, transforming variables), particularly when alternative decisions would also have been reasonable.
   *	*p*-values between .01 and .05—especially across multiple studies. When the effect is real, unbiased statistical tests should produce heavily-skewed distributions of *p*-values, with most *p*-values below .01.
   *  Conducting many statistical tests (e.g., testing three separate DVs) but failing to correct for family-wise error rates / multiple comparisons.
   *	Optional stopping—unclear stopping rules for data collection. Inconsistent or strange sample sizes could be a clue.
* **S2.** HARKing (Hypothesizing After the Results are Known):
   *	When there is no significant effect overall, changing the focus to a subgroup where the effect is significant (e.g., “it works for women”).
   *	Changes in the direction of the effect across studies, or in the specific pattern observed, that are still interpreted as consistent with theory despite a lack of theoretical justification.
* **S3.** Low statistical power or precision (small sample size/number of observations).
* **S4.** Interpreting a result as evidence of “no difference” or “no effect” based just on a non-significant *p*-value without actually testing for evidence of absence (e.g., using equivalence testing or Bayesian stats). This often happens for non-central hypothesis tests, like ruling out potential confounds or alternative explanations.
* **S5.** Not actually testing the effect of interest (e.g., reporting that two effects are different from each other because one is statistically significant and the other is not, rather than testing the interaction directly).
* **S6.** Floor or ceiling effects, or other restriction of range problems. 
* **S7.** Effect sizes driven—or exaggerated—by outliers. 
* **S8.** Using wrong or inappropriate statistical techniques (e.g., doing a median split on a continuous variable). 
* **S9.** Violating important assumptions of statistical tests (e.g., ignoring interdependence or clustering in data, e.g., analyzing groups or couples as individuals).
* **S10.** Threats to measurement invariance—if there is a reason to worry that the same measure could have different meaning in different groups or at different times.
* **S11.** Complicated effects reported without cross-validation or direct replication that are susceptible to overfitting or spurious effects:
   *	Moderated mediation. 
   *	Causal models with many links/paths.
   *	Higher order interactions—even a two-way interaction can be reason for skepticism, but especially three-way or higher.
* **S12.** Reporting significant interactions with effects that are driven by patterns other than the theory would predict (e.g., if the theory would say that cell A1 should be lower than cells A2, B1, and B2, but the pattern of results does not look like that).
* **S13.** Claiming implausibly large effect sizes, or otherwise too-perfect data (e.g., means are perfectly equally spaced apart, barely overlapping distributions).
* **S14.** Claiming evidence for an effect with a *p*-value larger than .05, or inconsistent application or interpretation of the *p*-value thresholds (i.e., playing fast and loose with alpha). 
* **S15.** Controlling for variables that were measured with error, without using latent variables or otherwise taking the error into account.

## Internal Validity

Internal validity refers to whether claims about the causal relationships among variables are warranted by the evidence. To assess internal validity, compare the authors’ claims about causal relationships (if any) with what the study design could reasonably allow with respect to causal claims. Sometimes claims about causality are implied rather than stated explicitly.

### Common potential threats to internal validity:

#### In the context of experimental designs:
* **I1.** Confounds that are part of the manipulation—the manipulation likely affected other variables. besides the independent variable (this is also a threat to the construct validity of the manipulation).
* **I2.** Confounds outside of the manipulation—conditions differ in ways besides the manipulation. 
* **I3.** Poor/weak manipulations—too subtle or unlikely to be manipulating the construct of interest. 
* **I4.** No true control condition, or the control condition was not similar enough to the experimental condition (did not have exactly the same experience as the experimental condition, besides the manipulated variable).
* **I5.** Demand effects—participants responding to what they think they are supposed to say/do or what they think the experimenter wants them to say/do. This may be especially likely in within-subjects designs, but can also happen in between-subjects designs.
* **I6.** Non-random assignment to conditions. 
* **I7.** Having many participants drop out after the manipulation (messes up random assignment).
* **I8.** Incorrect use and/or interpretation of mediation analyses.

#### In the context of correlational/observational designs:
* **I9.** Ignoring possible third variables (e.g., selection effects, confounds). 
* **I10.** Ignoring possible reverse causality.
* **I11.** Making unwarranted assumptions to rule out alternative explanations. 
* **I12.** Controlling for things that should not be controlled for (e.g., a potential mediator or collider) or throwing in a bunch of controls that seem haphazard.
* **I13.** Controlling for variables that were measured with error, without using latent variables or otherwise taking the error into account.
* **I14.** Regression to the mean (if participants were selected based on extreme scores)
* **I15.** Incorrect use and/or interpretation of mediation analyses.

## External Validity

External validity refers to the validity of generalizations made from the data. This includes generalizations made to other people, other times, other settings (e.g., lab to real world), other stimuli, other measures or manipulations, and other ways of testing the same research question (including everything from other experimenters to other recruitment strategies and more). Few studies can fully justify these kinds of generalizations, yet many such claims are made—whether implicitly or explicitly.  

### Common potential threats to external validity:
* **E1.** Claiming effects generalize to a population of participants, measures/manipulations, or settings not sampled in the study—particularly when there is reason to doubt the plausibility of the claim.
  *	It can even be risky to claim that the effect applies to a specific subset of participants, measures/manipulations, or settings that were sampled, if the authors did not directly test whether the effect holds in that specific subset of the data (e.g., making claims about an effect being true for older adults when the sample and analyses include both younger and older adults and the authors did not test if the effect holds across age groups).
* **E2.** Examining only a narrow slice of the construct of interest (e.g., using a single or just a couple stimuli or vignettes).
* **E3.** Contrived lab setting or lack of realism (e.g., using a hypothetical scenario instead of a real situation, reducing a complex experience like trauma to a trivial manipulation like getting a crappy prize).
* **E4.** Recruiting participants from inappropriate populations (e.g., sampling only college students when studying a phenomenon like workplace misconduct that is likely to vary widely by age/experience).
* **E5.** Making claims based on data from a convenience sample that would require a representative sample (e.g., claims about frequency or absolute levels of a single variable such as “80% of women have experienced discrimination”).


#### Acknowledgements: 
This document is inspired by Shadish, Cook, & Campbell (2002) Experimental and Quasi-Experimental Designs for Generalized Causal Inference, and Morling (2017) Research Methods in Psychology. We are grateful to our research group at UC Davis, Daniël Lakens, Fiona Fidler, and Eden Smith, for feedback.  All errors and stupidities are ours.  
