---
layout: page
title: Research
permalink: /research/
---
# Current Projects
<div class="wrapperTop">
  <div class="oneTop">
  <img class="ohbm-image" src="/assets/img/brain1.jpg" alt="brain1" style='height: 100%; width: 100%; object-fit: contain'/>
  </div>
  <div class="twoTop">
  <img class="ohbm-image" src="/assets/img/floc.png" alt="floc" style='height: 100%; width: 100%; object-fit: contain'/>
  </div>
  <div class="threeTop">
  <img class="ohbm-image" src="/assets/img/devo.png" alt="devo" style='height: 100%; width: 100%; object-fit: contain'/>
  </div>
  <div class="fourTop">
  <u>Function and Cytoarchitecture</u> <br> 
  Created cortical mesh reconstructions of post-mortem human brains in FreeSurfer based on hand segmentations. The surfaces were used to create maximum probability maps (MPM) of cytoarchitechtonic regions of interest (cROI) in the fusiform gyrus. I created a pipeline using the cortex based alignment tools of FreeSurfer to register these MPM cROIs to individual living subjects. For the first time, this allowed the quantification of proportion overlap of category selective regions of VTC and its cellular composition.
  </div>
</div>
***
# Past Projects
 <div class="wrapper">
  <div class="one">
  <img class="ohbm-image" src="/assets/img/brain1.jpg" alt="brain1" style='height: 100%; width: 100%; object-fit: contain'/>
  </div>
  <div class="two">
  <img class="ohbm-image" src="/assets/img/floc.png" alt="floc" style='height: 100%; width: 100%; object-fit: contain'/>
  </div>
  <div class="three">
  <img class="ohbm-image" src="/assets/img/devo.png" alt="devo" style='height: 100%; width: 100%; object-fit: contain'/>
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

.wrapperTop {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
  grid-auto-rows: minmax(100px, auto);
  }
.oneTop {
  grid-column: 1 / 2;
  grid-row: 1;
  padding: 10px;
  }
.twoTop {
  grid-column: 2 / 2;
  grid-row: 1 ;
  padding: 10px;
}
.threeTop {
  grid-column: 1 / 2;
  grid-row: 2;
  padding: 10px;
}
.fourTop {
  grid-column: 2 / 2;
  grid-row: 2;
  padding: 10px;
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