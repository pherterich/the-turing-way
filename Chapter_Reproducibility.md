# What is reproducible science?

## Summary
> to be written

## How this will help you/ why this is useful
This chapter sets out the definition of reproducibility that the Turing Way project team used when writing this handbook. It will be the 

## Prerequisites / recommended skill level
No previous knowledge needed. 

### Definition/glossary
> Link to the glossary here or copy in key concepts/definitions that readers should be aware of to get the most out of this chapter

## Chapter content 

### Definitions of reproducibility

> Copied from ROpenSci Reproducibility Guide - PH to figure out licensing/re-use

Victoria Stodden [(2014)](http://edge.org/response-detail/25340), a prominent scholar on this topic, has identified some useful distinctions in reproducible research:

- _Computational reproducibility_: when detailed information is provided about code, software, hardware and implementation details.

- _Empirical reproducibility_: when detailed information is provided about non-computational empirical scientific experiments and observations. In practise this is enabled by making data freely available, as well as details of how the data was collected.

- _Statistical reproducibility_: when detailed information is provided about the choice of statistical tests, model parameters, threshold values, etc. This mostly relates to pre-registration of study design to prevent p-value hacking and other manipulations. 

[Stodden et al. (2013)](http://stodden.net/icerm_report.pdf) place **computational reproducibility** on a spectrum with five categories that account for many typical research contexts:

- _Reviewable Research_. The descriptions of the research methods can be independently assessed and the results judged credible. (This includes both traditional peer review and community review, and does not necessarily imply reproducibility.)
- _Replicable Research_. Tools are made available that would allow one to duplicate the results of the research, for example by running the authors’ code to produce the plots shown in the publication. (Here tools might be limited in scope, e.g., only essential data or executables, and might only be made available to referees or only upon request.)
- _Confirmable Research_. The main conclusions of the research can be attained independently without the use of software provided by the author. (But using the complete description of algorithms and methodology provided in the publication and any supplementary materials.)
- _Auditable Research_. Sufficient records (including data and software) have been archived so that the research can be defended later if necessary or differences between independent confirmations resolved. The archive might be private, as with traditional laboratory notebooks.
- _Open or Reproducible Research_. Auditable research made openly available. This comprised well-documented and fully open code and data that are publicly available that would allow one to (a) fully audit the computational procedure, (b) replicate and also independently reproduce the results of the research, and (c) extend the results or apply the method to new problems.

### The Turing Way definition of reproducibility

The Turing Way project will define reproducible research as both data and code being available to fully rerun the analysis.
![Kirstie's definition of reproducible research](https://github.com/pherterich/the-turing-way/blob/master/reproducibility_kirstie.png)
However, we recognize that some research will use sensitive data that cannot be shared and this handbook will provide guides on how your research can be reproducible without all parts necessarily being open.

## Checklist/Exercise
- [ ] define reproducibility for yourself

## What to learn next?
> recommended next chapters that are a good next step up

## Bibliography 

Stodden, V., Borwein, J., & Bailey, D. H. (2013). Setting the default to reproducible. computational science research. SIAM News, 46(5), 4-6. http://stodden.net/icerm_report.pdf

Whitaker, Kirstie (2018): Barriers to reproducible research (and how to overcome them). figshare. Paper. https://doi.org/10.6084/m9.figshare.7140050.v2

## Additional material 
### Recommended reading
> top 3/5 resources to read on this topic (if they weren't licensed so we could include them above already)

### Other useful links
> less relevant/favourite resources in case someone wants to dig into this in detail