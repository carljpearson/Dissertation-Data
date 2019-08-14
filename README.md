# Dissertation-Data
Here is the data from my dissertation experiments. This will briefly describe variables in each csv file. These are long format data with each case being a single trial of a participant. 'og' indicates original text output from Qualtrics.

## Experiment 1

"ResponseId"     

A unique identifer for each participant.

"group"          

Indicates belong to one of four experimental combinations. 'an-low' is low analytical risk and 'an-high' is high analytical risk. 'af-low' is low affective risk and 'af-high' is high affective risk.

"analytical"     

Analytical risk split out from "group".

"affective"      

Affective risk split out from "group".

"trial_og"      

The filename of the x-ray image on the trial. 'Y' indicates no contraband (clear) and 'x' indicates contraband (NOT clear). The number is the unique identifier of that image within its contraband class.

"dec_og"         

Initial decision on a trial. 'Use AWD decision' indicates reliance, 'Peak at AWD' indicates peeking behavior, 'Check (contraband present)' indicates a decision that there is contraband, and 'Clear (NO contraband present)' indicates a decision there is no contraband.

"pea_og"  

Indicates response if the user peeked at automation recommendation (NA is peeking did not occur).


"auto.correct"   

Based on a the data key for if the automation is correct in the trial, regardless of it the participant relied on automation.

"block"          

The block (0-3) that the trial belonged to.

"trial_type"    

Contraband class split out from "trial_og".

"trial_order"    

The order value (1-15) of the trial within its block, as trials are randomized within a block.

"pilot.acc"      

Percentage accuracy of the same x-ray slide outcomes in our pilot.

"acc"       

Accuracy of participant in trial (0 = wrong, 1 = right).

"rely"  

Reliance of participant in trial (0 = did not rely, 1 = relied).

"bt"       

Reliance {behavioral trust} of participant in trial ONLY if peeking occured (0 = did not rely, 1 = relied).

"negative"  

Averaged negative item PANAS scores in the "block".

"positive"       

Averaged positive item PANAS scores in the "block".

"trust"         

Average trust score in the "block".

"propensity"     

Average trust propensity for the participant.

"trust_centered"

Grand mean centered trust score in the "block".

"affective_num"  

Numerical version of "affective".

"analytical_num"

Numerical version of "analytical".
