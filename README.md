# optimize-it
Optimization code and documentation for isotope trace (IT) detection in mass spectrometry applications of the Bioconductor package [XCMS](http://www.bioconductor.org/packages/release/bioc/html/xcms.html) .  

### Visual Optimization
Visualization is the quickest way to optimize IT detection with Massifquant in the XCMS suite.  The strategies and methods detailed in:  
  + optimize-vis-massifquant.Rnw      (source code)
  + optimize-vis-massifquant.pdf      (human readable version)

show how to precisely visualize the effects of parameter variations on the IT detection results. The **mouse_data** and **figs** directories correspond to this analysis.  

### Score-Based Optimization
A score-based optimization is possible with a corresponding ground truth annotation of veritable IT sets and a carefully constructed evaluation metric (e.g. f-score). The document
  + reproducing-greedy-search-optimization-figures.pdf  
  
details the greedy-search approach as well as how to reproduce the analysis depicted in the Massifquant publication. The compressed folder **gate-reproducible.tgz** has all the relevant data and scripts to reproduce the entire analysis.   
