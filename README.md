# Transmission of grapevine fanleaf virus by Xiphinema index
Code and data required for the analysis of Roy et al. under review

## The following R Markdown files are listed with their associated data dependency files. 
  
<ul>
  <li>StandardCurves2.Rmd - Analysis of qPCR data from virus purifications and all RT-qPCR on nematode samples
    <ul>
      <li>"Standard Curves Full.csv"</li>
      <li>"Experiment1Combined_qPCR_Xindex.xlsx"</li>
      <li>"Experiment2_2Combined_qPCR_Xindex.xlsx"</li>
      <li>"Nematode_Samples_with_Normalized_Values.csv"</li>
    </ul>
  </li>
  <li>TwoStepTransmissionAssay.Rmd - Statistical analysis of two-step transmission assay with X. index and various GFLV host plants
    <ul>
      <li>"herbaceous_to_vitis.csv"</li>
      <li>"same_species_transmission.csv"</li>
    </ul>
  </li>
  <li>XindexDispersalAnalysis.Rmd - Location and count analysis of recovered nematodes from experimental bins in continuous transmission experiments
    <ul>
      <li>"XindexPop2.xlsx"</li>
    </ul>
  </li>
  <li>RhizoAnalysisTransmission.Rmd - Complete Rhizovision root trait analysis of experimental plants in continuous transmission assays
    <ul>
      <li>"Rhizo_TransmissionAssay1.xlsx"</li>
      <li>"Rhizo_TransmissionAssay2.xlsx"</li>
      <li><em>dependency:</em> Merging with data frames made in previous .Rmd files</li>
    </ul>
  </li>
  <li>Acquisition to root traits.Rmd - Correlation analysis of root traits, GFLV titer, and transmission events in continuous assays
    <ul>
      <li>No extra files needed, analysis is done after other R Markdown files have been executed and loaded</li>
    </ul>
  </li>
</ul>
