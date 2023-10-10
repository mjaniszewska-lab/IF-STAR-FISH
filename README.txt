COUNT MATRICIES:
For each case, 5 images were taken from the primary tumor and 5 images were taken from the recurrent tumor. The pipeline produces a count matrix (CM) file that includes information from all 5 images together in the same document. 

Each row corresponds to a nucleus within each image
Each column represnts the following:
A - ImageNumber: Which image the nucleus comes from
B - ObjectNumber: The unique numerical label for each nucleus
C - AreaShape: pixel based area of each nuclear object
D - Children_CDK4_Segment_Count: Number of FISH speckles quantified within each nucleus from the CDK4 channel
E - Children_EGFR_Segment_Count: Number of FISH speckles quantified within each nucleus from the EGFR channel
F - Children_PDGFRA_Segment_Count: Number of FISH speckles quantified within each nucleus from the PDGFRA channel
G - Children_TERT_C228T_Segment_Count: Number of STAR-FISH speckles quantified within each nucleus from the STARFISH channel
H - Location_Center_X: X coordinate of the center of the nuclear object 
I - Location_Center_Y: Y coordinate of the center of the nuclear object 
J - Math_Percent_CDK4: Percentage of nuclear object occupied by CDK4 FISH signal
K - Math_Percent_EGFR: Percentage of nuclear object occupied by EGFR FISH signal
L - Math_Percent_PDGFRA: Percentage of nuclear object occupied by PDGFRA FISH signal
M - Parent_CD31_Segment: The mean of the child object (nuclei segment) measurements, calculated for each parent object (CD31 segment). Number greater than zero indicates marker positivity
N - Parent_CD45RO_Segment: The mean of the child object (nuclei segment) measurements, calculated for each parent object (CD45RO segment). Number greater than zero indicates marker positivity
O - Parent_HIF1a_Segment: The mean of the child object (nuclei segment) measurements, calculated for each parent object (HIF1a segment). Number greater than zero indicates marker positivity
