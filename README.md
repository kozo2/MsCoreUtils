# Low level functions for MS data

[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![build status](https://travis-ci.org/rformassspectrometry/MsCoreUtils.svg?branch=master)](https://travis-ci.org/rformassspectrometry/MsCoreUtils)
[![codecov.io](https://codecov.io/github/rformassspectrometry/MsCoreUtils/coverage.svg?branch=master)](https://codecov.io/github/rformassspectrometry/MsCoreUtils?branch=master)
[![license](https://img.shields.io/badge/license-Artistic--2.0-brightgreen.svg)](https://opensource.org/licenses/Artistic-2.0)

[![years in bioc](http://bioconductor.org/shields/years-in-bioc/MsCoreUtils.svg)](https://bioconductor.org/packages/release/bioc/html/MsCoreUtils.html)
[![bioc downloads](http://bioconductor.org/shields/downloads/MsCoreUtils.svg)](https://bioconductor.org/packages/stats/bioc/MsCoreUtils/)
Release: [![build release](http://bioconductor.org/shields/build/release/bioc/MsCoreUtils.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/MsCoreUtils/)
Devel: [![build devel](http://bioconductor.org/shields/build/devel/bioc/MsCoreUtils.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/MsCoreUtils/)

<img
src="https://raw.githubusercontent.com/rformassspectrometry/stickers/master/MsCoreUtils/MsCoreUtils.png"
height="150">

`MsCoreUtils` defines low-level functions for mass spectrometry data and is
independent of any high-level data structures.
These functions include mass spectra processing functions
(noise estimation, smoothing, binning),
quantitative aggregation functions (median polish, robust summarisation, ...),
missing data imputation, data normalisation (quantiles, vsn, ...)
as well as misc helper functions, that are used across high-level
data structure within the
[R for Mass Spectrometry packages](https://www.rformassspectrometry.org/pkgs/).

# Contributions

- Sigurdur Smarason (@SiggiSmara): weighted moving average (https://github.com/sgibb/MALDIquant/pull/54)
- Thomas Naake (@tnaake): dotproduct calculation (https://github.com/rformassspectrometry/MsCoreUtils/pull/17)
- Adriaan Sticker: `robustSummary` aggregation function (originally contributed to `MSnbase`)
