This repository contains resources for the mousetrap suite, a collection of open-source software packages for creating and analyzing movement tracking experiments. The resources are presented separately for the different publications they are supporting.


### Wulff, Kieslich, Henninger, Haslbeck & Schulte-Mecklenbeck (2021)

This article presents a tutorial to movement tracking of cognitive processes with the [mousetrap R package](http://pascalkieslich.github.io/mousetrap/). Using the [data](http://pascalkieslich.github.io/mousetrap/reference/KH2017_raw.html) collected in Kieslich & Henninger (2017), the tutorial covers the complete analysis process, starting with the raw data import, various algorithms for processing, analyzing and visualizing movement trajectories, as well as novel methodology for classifying movement trajectory types. All analyses performed in this tutorial can be replicated using the accompanying analysis script available as [R Markdown](Kieslichetal2019_chapter/tutorial_analyses.Rmd) (code only) and [HTML](Kieslichetal2019_chapter/tutorial_analyses.pdf) (code including output).

### Wulff, Haslbeck, Kieslich, Henninger & Schulte-Mecklenbeck (2019)

This [book chapter](https://doi.org/10.4324/9781315160559-10) introduces novel methods for identifying and classifying movement trajectories types. These methods are implemented and documented in the [mousetrap R package](http://pascalkieslich.github.io/mousetrap/reference/mousetrap.html#cluster-functions). A preprint of the book chapter is available on [PsyArXiv](https://psyarxiv.com/6edca/).


### Kieslich, Henninger, Wulff, Haslbeck & Schulte-Mecklenbeck (2019)

This [book chapter](https://doi.org/10.4324/9781315160559-9) provides an introduction to creating mouse-tracking experiments using the [mousetrap plugin for OpenSesame](https://github.com/pascalkieslich/mousetrap-os) and to analyzing mouse-tracking data using the [mousetrap R package](http://pascalkieslich.github.io/mousetrap/). A preprint of the book chapter is available on [PsyArXiv](https://psyarxiv.com/zuvqa/). In the chapter, an example experiment is created following Experiment 1 by [Dale et al. (2007)](https://doi.org/10.3758/BF03195938). The example experiment is provided as an [OpenSesame file](Kieslichetal2019_chapter/tutorial_experiment.osexp). The chapter also demonstrates the analysis of mouse-tracking data, for which the analyses scripts are available as [R Markdown](Kieslichetal2019_chapter/tutorial_analyses.Rmd) (code only) and [PDF](Kieslichetal2019_chapter/tutorial_analyses.pdf) (code including output).


### Kieslich & Henninger (2017)

This [article](https://doi.org/10.3758/s13428-017-0900-z) presents the [mousetrap plugin for OpenSesame](https://github.com/pascalkieslich/mousetrap-os). An example experiment is created following Experiment 1 by [Dale et al. (2007)](https://doi.org/10.3758/BF03195938). The [complete experiment](KieslichHenninger2017/experiment/experiment_german_full_version.osexp) (in German) and a [simplified version](KieslichHenninger2017/experiment/experiment_english_simplified.osexp) (in English) are provided. A study was conducted using this experiment and the collected data (which are included in the [mousetrap R package](http://pascalkieslich.github.io/mousetrap/reference/KH2017_raw.html)) are used to demonstrate a number of simple analyses. The analyses scripts are provided as [R Markdown](KieslichHenninger2017/KH2017_analyses.Rmd) (code only) and [PDF](KieslichHenninger2017/KH2017_analyses.pdf) (code including output). A [separate script](KieslichHenninger2017/KH2017_analyses_following_Dale_et_al.pdf) replicates the original analyses by Dale et al. (2007).
