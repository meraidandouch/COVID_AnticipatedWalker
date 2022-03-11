# RBM_RandomWalker

## Contributor: Merai Dandouch

### Description: 
This repository has code for a anticipated mutational drift script that determines the next variant. It uses the RBM region of UFP04971.1[OMICRON] as a base and mutates it based off the likelhood probability of mutating. This potentially could be used by scientist to create a vaccine that anticipates mutations and evolves with virus. The vaccine should focus on the rbm regions due to high variability and significance of transmissibility in this region. Below there is a series of phylogenetic trees representing the multi-sequence alignment between the spike protein region, RBD region, and the RBM region. The RBD region shares a similar relationship to the spike protein phylogetnic tree. However,the OMICRON RBM region diverges to form a clade on its own. 



-	we mutated regions in the OMICRON variant sequences that are most likely to mutate based off: 
o	the sequence logo in previous slides to determine conserved regions 
o	the freq of each aa in each RBM 
o	Percentages from literature, where we found that spike proteins share 76% total identity : (Shah et al. 2020.)


-	We did another phylogenetic analyses using the new sequence, and just like we predicted the new variant diverges and is the outgroup to the remaining corona family which makes sense
![image](https://user-images.githubusercontent.com/16998734/157922103-c36cb5f5-ab8a-4137-b6bc-f707201a2d39.png)
