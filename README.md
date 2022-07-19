# RBM_AnticipatedWalker

## Contributors: Merai Dandouch, Kyra Griffin Mitchell, Vridhi Vinaykiya

### Description: 
This repository has code for a anticipated mutational drift script that determines the next variant. It uses the RBM region of UFP04971.1[OMICRON] as a base and mutates it based off the liklehood probability of mutating. This potentially could be used by scientist to create a vaccine that anticipates mutations and evolves with virus. The vaccine should focus on the rbm regions due to high variability and significance of transmissibility in this region. Below there is a series of phylogenetic trees representing the multi-sequence alignment between the spike protein region, RBD region, and the RBM region. The RBD region shares a similar relationship to the spike protein phylogetnic tree. However,the OMICRON RBM region diverges to form a clade on its own. 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/16998734/157924479-76e71eca-5ce1-455f-963d-fc43da2656ce.png">
<img width="468" alt="image" src="https://user-images.githubusercontent.com/16998734/157923880-17a5ea20-9bdb-4155-ac35-e22542afb23f.png">

### Mutated regions in the OMICRON variant sequences that are most likely to mutate based off: 
* the sequence logo determining conserved regions 
  * <img width="228" alt="image" src="https://user-images.githubusercontent.com/16998734/157924995-66525d9d-59b5-4e39-985a-ad812f3d29ce.png">
* the freq of each aa in each RBM 
* Percentages from literature, where spike proteins share 76% total identity : (Shah et al. 2020.)

### Result
Another phylogenetic analyses using the new sequence,the new variant diverges and is the outgroup to the remaining corona family which makes sense

<img width="468" alt="image" src="https://user-images.githubusercontent.com/16998734/157924453-97930f3f-e3b7-497d-8845-4ffcc0b295f8.png">


## Going Forward 
* Improve on these analyses by grabbing more samples from NCBI
* Provide more statistical support using nueral networks machine learning algorithms 
