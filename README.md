
In addition to assisting researchers with their research, we also
develop tools to assist with various tasks (primarily statistical and
reporting). In the spirit of open science, we share these tools on
various sharing platforms.

## R packages

R is one of the two main statistical programming languages used at CTU
Bern. During out work, we have developed the following packages for
various tasks.

### [`accrualPlot`](https://github.com/CTU-Bern/accrualPlot) <img src='https://github.com/CTU-Bern/accrualPlot/raw/main/man/figures/sticker.png' align="right" height="150">

With `accrualPlot`, it is easy to depict recruitment in a manner similar
to a cumulative incidence curve, as a bar plot or to estimate the time
point at which a given number of participants will be been enrolled.

<img src='https://github.com/CTU-Bern/accrualPlot/raw/main/man/figures/README-unnamed-chunk-3-1.png'>

More information on `accrualPlot` is available
[here](https://ctu-bern.github.io/accrualPlot).

### [`btabler`](https://github.com/CTU-Bern/btabler) <img src='https://github.com/CTU-Bern/btabler/raw/main/man/figures/sticker.png' align="right" height="150">

`btabler` is a wrapper around the
[`xtable`](https://cran.r-project.org/web/packages/xtable/) package
allowing more optimized tables for use in LaTeX reports.

<img src='https://github.com/CTU-Bern/btabler/raw/main/vignettes/fig/header.png' class="center">

More information on `btabler` is available
[here](https://ctu-bern.github.io/btabler/).

### [`HSAr`](https://github.com/CTU-Bern/HSAr)

`HSAr` is a by-product of CTU Bern’s involvement in the SNFs [Smarter
Health Case National Research Programme
(NRP74)](http://www.nfp74.ch/en/Pages/Home.aspx). It provides an
approach for creating so-called Hospital Service Areas - aggregated
areas supposed to reflect the patterns of flow from people live to where
they go to hospital. The method is described
[here](https://onlinelibrary.wiley.com/doi/full/10.1111/1475-6773.13275).
(The main repository is [here](https://github.com/aghaynes/HSAr))

### [`kpitools`](https://github.com/CTU-Bern/kpitools) <!-- <img src='https://github.com/CTU-Bern/kpitools/man/figures/sticker.png' align="right" height="200"> -->

`kpitools` is for risk based monitoring. It provides a consistent
approach to calculating and reporting quality indicators (i.e. Key
Performance Indicators, KPIs).

### [`presize`](https://github.com/CTU-Bern/presize) <!-- <img src='https://github.com/CTU-Bern/presize/man/figures/sticker.png' align="right" height="200"> -->

`presize` is a package for precision based sample size calculations.
Rather than having a specific hypothesis to test, a trial might be
rather aimed at estimating the magnitude of a effect and want to have an
estimate with a certain precision (e.g. ‘how wide would my confidence
interval be with so-and-so many participants?’, or ‘how many
participants would be required to attain a confidence interval so
wide?’).

`presize` is available on
[CRAN](https://cran.r-project.org/web/packages/presize) and an
user-friendly, non-programmatic version of the application is available
[here](https://shiny.ctu.unibe.ch/presize/).

## Stata

Stata is the second programming language primarily used at CTU Bern.
Again, we have developed various codes that may be of general interest
to users.

### [`btable`](https://github.com/CTU-Bern/btable) <img src='https://github.com/CTU-Bern/btable/raw/main/sticker.png' align="right" height="150">

`btable` makes creating baseline tables simple in Stata. It is a very
flexible approach used by most statisticians at CTU Bern, even those
that primarily use R for their analyses.

### [`stata_secutrial`](https://github.com/CTU-Bern/stata_secutrial)

This repository contains code for reading secuTrial data into Stata and
does a lot of preparatory tasks such as labelling variables and
formatting dates.

## Other packages…

CTU Bern was also actively involved in programming the
[`secuTrialR`](https://github.com/SwissClinicalTrialOrganisation/secuTrialR)
package for loading secuTrial datasets in to R.