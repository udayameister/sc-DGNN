This is a sample dataset comprising synthetic network data simulating classification problems. 
The synthetic network data was generated using the "gen_synthData.m" function provided
within the NBS-Predict toolbox. 

The dataset comprises 200 connectivity matrices (100 control vs. 100 contrast) with the shape of 116x116 
(i.e., AAL atlas). Of the total number of 6670 edges in each connectivity matrices, 67 edges contain contrast 
the noise ratio of 0.5. The data generation process is described in detail in the paper below.

Please keep in mind that any results from this dataset does not imply any significant information since it 
is only a synthetic dataset. Instead, this sample data should only be used to check whether the
toolbox works properly. Also, this dataset serves as an example of a proper input structure; 
thus users should organize their input files accordingly. 

The contrast values used to analyze this specific sample data should be [1, -1]. 

The main files and folders required for the analysis are "BrainRegions.csv", "design.mat", and "CorrMat". 

There is also an "AdditionalFiles" folder comprising of "contrastEdgeIdx.mat" including vectorized 
indices of relevant edges, and "RelevantEdges.pdf" showing the adjacency matrix of relevant edges. 
Users can compare the subnetworks obtained following the analysis with the adjacency matrix of the 
relevant edges shown in the pdf file to see how likely they could detect the relevant edges.

If you use the NBS Predict toolbox, please cite the following publication:
    Serin, E., Zalesky, A., Matory, A., Walter, H., & Kruschwitz, J. D. (2021). 
    NBS-Predict: A Prediction-based Extension of the Network-based Statistic. NeuroImage, 118625.

Please get in touch with Emin Serin (emin.serin@charite.de) or Johann Kruschwitz (johann.kruschwitz@charite.de) 
for further questions. 