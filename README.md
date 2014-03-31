# optimize-it
Optimization code and documentation for isotope trace detection in mass spectrometry applications of XCMS.  
### Visual Optimization
Visualization is the quickest way to optimize isotope trace detection with Massifquant in the XCMS suite. The files 
  * optimize-vis-massifquant.Rnw Source Code
  * optimize-vis-massifquant.tex: Latex encoding of source code
  * optimize-vis-massifquant.pdf: Human readable version  
detail how to strategically visualize the effects of parameter variations on the IT detection results. The **mouse_data** and **figs** directories correspond to this analysis.   
### Score-Based Optimization
As described in the publication of Massifquant, a score-based optimization is possible with a corresponding ground truth annotation and a carefully constructed evaluatio metric (e.g. f-score). The document
  *reproducing-greedy-search-optimization-figures.pdf  
details the greedy-search approach as well as how to reproduce the analysis depicted in the Massifquant publication.  
