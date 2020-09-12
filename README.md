# mqz_ComDock_docking
ComDock: a novel approach for protein-protein docking with an efficient fusing strategy
====

In this paper, a new, diversity, comprehensive template library is constructed from PDB, containing 77,685 complexes. ComDock is a hybrid approach for protein-protein docking which combines the effectivity of template-based method (TemDock) model and the universality of ab initio (ZDOCK) model. TemDock retrieves the evolutionary relationship between the target sequence and samples in template library we construct and transfers similar structural information. Then, the target structure is built by superposing on the homologous template complex with TM-align. On 105 targets with templates from Benchmark 5.0, the TemDock and ComDock achieve a success rate of 66.67% and 69.52% in the top 10 conformations, respectively. Comparing with the HDOCK, ComDock obtains better I-RMSD of hit configurations on 6 targets. As an efficient method for protein-protein docking, the ComDock is expected to study the protein-protein recognition and reveal the various biological passway that are critical for developing drug discovery.

*   The architecture of ComDock
![](https://github.com/unimqz/mqz_ComDock_docking/raw/master/flowchart_docking-V9-(a,b).png) 

*   The construction of template library
![](https://github.com/unimqz/mqz_ComDock_docking/raw/master/dataset_construction_new.png) 
