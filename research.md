---
layout: page
title: Research
permalink: /research/
---
# Current Projects
<div class="row">
  <div class="column" markdown="1">
  I am a graduate student in the Department of Psychology at University of Pennsylvania where I am co-advised by David Brainard and Geoffrey Aguirre. My current research uses functional magnetic resonance imaging, computational, and behavioral techniques to study the neural basis of cortical color responses. <br><br> Previously I was a lab manager for Kalanit Grill-Spector at Stanford University. During this time, I had two main projects where I examined the development of high-level vision and the microarchitecture of functional regions in human cortex . Prior to being a lab manager, I was a research assistant for Emily Grossman at UC Irvine where I worked on understanding the neural representation of biological motion.
  </div>
  
  <div class="column">
  <img class="ohbm-image" src="/assets/img/ohbm.jpg" alt="OHBM 2015" style="width:350px;height:350px;">
  </div>
</div> 

***
# Past Projects
 <div class="wrapper">
  <div class="one">
  <img class="ohbm-image" src="/assets/img/brain1.jpg" alt="brain1" style="width:350px;height:350px;">
  </div>
  <div class="two">
  <img class="ohbm-image" src="/assets/img/floc.png" alt="floc" style="width:350px;height:350px;">
  </div>
  <div class="three">
  <img class="ohbm-image" src="/assets/img/devo.png" alt="devo" style="width:350px;height:350px;">
  </div>
  <div class="four">
  <u>Function and Cytoarchitecture</u> <br> 
Created cortical mesh reconstructions of post-mortem human brains in FreeSurfer based on hand segmentations. The surfaces were used to create maximum probability maps (MPM) of cytoarchitechtonic regions of interest (cROI) in the fusiform gyrus. I created a pipeline using the cortex based alignment tools of FreeSurfer to register these MPM cROIs to individual living subjects. For the first time, this allowed the quantification of proportion overlap of category selective regions of VTC and its cellular composition.
  </div>
  <div class="five">
  <u>Predictive Atlas of High Level Visual Areas</u><br>
Category selective functional regions of interest (fROI) were used to create maximum probability maps (MPM) of ventral temporal cortex. Using cortex based alignment, I registered these MPM fROIs to an average cortical surface and used a leave one out analysis that allowed for the quantification of the spatial predictability of these fROIs.
  </div>
  <div class="six">
  <u>Development of Perception</u><br>
A longitudinal research study examining human high-level visual cortex in children (5-12 years old) and adults. From this study, we found growth of tissue within portions of ventral temporal cortex, challenging the idea that cortex is either quiescent or pruned after early childhood. This tissue growth within face-selective cortex, is correlated with increases in the functional selectivity of face-selective regions and linked to improvements in recognition memory ability well into adulthood. To do this study, we combined quantitative magnetic resonance imaging techniques with functional MRI and behavioral measurements in single-subject analyses. We have also linked these measures with ex vivo quantifications of cytoarchitecture.
  </div>
</div>

<style type="text/css">
  .row {
    display: flex;
  }

  .column {
    flex: 50%;    
  }

.wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  grid-auto-rows: minmax(100px, auto);
}
.one {
  grid-column: 1 / 3;
  grid-row: 1;
}
.two {
  grid-column: 2 / 3;
  grid-row: 1 ;
}
.three {
  grid-column: 3 / 3;
  grid-row: 1;
}
.four {
  grid-column: 1 / 3;
  grid-row: 2;
}
.five {
  grid-column: 2 / 3;
  grid-row: 2;
}
.six {
  grid-column: 3 / 3;
  grid-row: 2;
}

  img.brain1 {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
img.floc {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
img.devo {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

</style>