# DPT_in_LocalEP
Codes and data for the paper "Discontinuous transition in explosive percolation via local suppression"
## Fig3. (a) ##
** Data **
'SuccessiveRewire_z4_n7_Pinf' using 1:2 : left line
'filter_SuccessiveRewire_z4_n15_Pinf' using 1:2 : right line
'MinBranchDet_z4_n7_Pinf' using 1:2 : squares
'MinBranchDet_z4_n15_Pinf' using 1:2 : circles
'MinBranchDet_z4_theory' using 1:2 : dashed line

** Code **
SuccessiveRewire.c was used to generate: 'SuccessiveRewire_z4_n7_Pinf' and 'filter_SuccessiveRewire_z4_n15_Pinf'.
MinBranchDet.c was used to generate: 'MinBranchDet_z4_n7_Pinf' and 'MinBranchDet_z4_n15_Pinf'.

## Fig3. (b) ##
** Data **
'SuccessiveRewire_z4_n9_fracRewire.bin.1.3' using 1:2 : squares
'SuccessiveRewire_z4_n15_fracRewire.bin.1.3' using 1:2 : circles

** Code ** 
SuccessiveRewire.c was used to generate these data files.

## Fig. 4(a) ##
** Data **
'GlobalRewire_SuccessiveBipartite_N16000_z3_TransG_p0.61' using 2:3 : empty squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_TransG_p0.62' using 2:3 : filled squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_TransG_pc' using 2:3 : empty circles
'GlobalRewire_SuccessiveBipartite_N16000_z3_TransG_p0.63' using 2:3 : filled circles
'GlobalRewire_SuccessiveBipartite_N16000_z3_TransG_p0.64' using 2:3 : triangles

** Code **
GlobalRewire_SuccessiveBipartite_nNotordered.c was used to generate these data files.

## Fig. 4(b) ##
** Data ** 
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_p0.61' using 2:($3*2) : empty squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_p0.62' using 2:($3*2) : filled squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_pc' using 2:($3*2) : empty circles
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_p0.63' using 2:($3*2) : filled circles
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_p0.64' using 2:($3*2) : triangles

** Code **
GlobalRewire_SuccessiveBipartite_nNotordered.c was used to generate these data files.

## Fig. 4(c) ##
** Data **
'GlobalRewire_SuccessiveBipartite_N1000_z3_nNotordered_steady' using 1:($2*2) : circles
'GlobalRewire_SuccessiveBipartite_N4000_z3_nNotordered_steady' using 1:($2*2) : filled squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotordered_Allseeds_Avg_steady' using 1:($2*2) : empty squares

** Code **
GlobalRewire_SuccessiveBipartite_nNotordered.c was used to generate these data files.

## Fig7. (a) ##
** Data **
'LocalRewire_SuccessiveBipartite_N1000_z3_T0.70_G' using 1:2 : line over squares
'filter_GlobalRewire_SuccessiveBipartite_N1000_z3_G' using 1:2 : squares
'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G' using 1:2 : line over cirles
'filter_GlobalRewire_SuccessiveBipartite_N16000_z3_G' using 1:2 : circles
'RPQ_Theory2_z3' using 1:($2+$3)/2 : dashed line

** Code **
LocalRewire_SuccessiveBipartite_G.c was used to generate: 'LocalRewire_SuccessiveBipartite_N1000_z3_T0.70_G' and 'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G'.
GlobalRewire_SuccessiveBipartite.c was used to generate: 'filter_GlobalRewire_SuccessiveBipartite_N1000_z3_G' and 'filter_GlobalRewire_SuccessiveBipartite_N16000_z3_G'.

## Fig7. (b) ##
** Data **
'LocalRewire_SuccessiveBipartite_N1000_z3_T0.70_G_meancluster_fracrewiring_nNotordered.linbin.0.005' using 1:($2*2) : squares (main panel)
'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G_meancluster_fracrewiring_nNotordered.linbin.0.005' using 1:($2*2) : circles (main panel)
'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G_meancluster_fracrewiring_nNotordered.linbin.0.02' using 1:($2*2) : inset

** Code **
LocalRewire_SuccessiveBipartite_nNotordered.c was used to generate these data files.

## Fig7. (c) ##
'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G_meancluster_fracrewiring.bin.1.3' using 1:4 : empty circles
'LocalRewire_SuccessiveBipartite_N8000_z3_T0.70_G_meancluster_fracrewiring.bin.1.3' using 1:4 : filled circles
'LocalRewire_SuccessiveBipartite_N4000_z3_T0.70_G_meancluster_fracrewiring.bin.1.3' using 1:4 : triangles
'LocalRewire_SuccessiveBipartite_N2000_z3_T0.70_G_meancluster_fracrewiring.bin.1.3' using 1:4 : filled squares
'LocalRewire_SuccessiveBipartite_N1000_z3_T0.70_G_meancluster_fracrewiring.bin.1.3' using 1:4 : empty squares

** Code **
LocalRewire_SuccessiveBipartite_nNotordered.c was used to generate these data files.
 
## Fig 8. (a) ##
** Data **
'GlobalRewire_SuccessiveBipartite_N1000_z3_nNotorderedInf_steady' using 1:($3*2) : circles
'GlobalRewire_SuccessiveBipartite_N4000_z3_nNotorderedInf_steady' using 1:($3*2) : filled squares
'GlobalRewire_SuccessiveBipartite_N16000_z3_nNotorderedInf_Allseeds_Avg_steady' using 1:($2*2) : empty squares

** Code **
GlobalRewire_SuccessiveBipartite_nNotorderedInf.c was used to generate these data files.
 
## Fig 8. (b) ##
** Data **
'maxSteadynNotorderedInf'

** Code **
GlobalRewire_SuccessiveBipartite_nNotorderedInf.c was used to generate this data file.

## Fig 8. (c) ##
** Data **
'LocalRewire_SuccessiveBipartite_N1000_z3_T0.70_G_meancluster_nNotorderedInf.linbin.0.002' using 1:($2*2) : bottom line
'LocalRewire_SuccessiveBipartite_N4000_z3_T0.70_G_meancluster_nNotorderedInf.linbin.0.002' using 1:($2*2) : center line
'LocalRewire_SuccessiveBipartite_N16000_z3_T0.70_G_meancluster_nNotorderedInf.linbin.0.002' using 1:($2*2) : top line

** Code **
LocalRewire_SuccessiveBipartite_nNotorderedInf.c was used to generate these data files.

## Fig 8. (d) ##
'maxEPnNotorderedInf'

** Code **
LocalRewire_SuccessiveBipartite_nNotorderedInf.c was used to generate this data file.

