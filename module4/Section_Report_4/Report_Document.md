***Report\_Document***



**Important Steps**



FastQC: Scans the raw reads and provides quality scores that either pass, warn, or fail. In the forward file, it contains multiple failed reports. 



FastP: Trimming the raw reads improving out quality reads. In the fastP file, a lot has been filtered.



HISAT: Aligns the genome for mapping next generation sequencing reads.



StringTie: To assemble the transcription and determines the gene expression levels.



FeatureCounts: To measure gene expression in DNA and RNA-Seq reads for genomic features.



DEseq2: Helps identify the different expressed features.



Creating a header: Allows us to input the top10anddown data for the matching genes later on.



Join two datasets: To merge datasets, giving out matches between the top 10 and down 10.





**Interpretation**



Volcano Plot: You can interpret based on the log fc and -log10 p-value, I can see that the red on the right are more regulated while the blue on the left are downregulated. The p-value indicates that the upregulated are more significant due to the height



Heatmap2 Plot: Compares the columns which are samples to the rows of genes. The color pink defines lower expression while green has higher expression, leaving white has a intermediate. With tree clusters both showing similarity.



DEseq2 Plot: (PCA Plot) There is a 78% variance meaning there's quite a bit variation. The mutant and wildtype have different expression, having the wildtype low biological variation.

(MA-Plot for Growth) There are blue dots which represents unregulated genes with the grey dots as downregulated.





**One up and one down regulated genes**



Gene:gene-BTH\_RS25855 is a protein that apart of the fimbrial system located in the outer membrane. It can contribute that affects the interactions of the bacteria and the formation of biofilm. Motility could change and even virulence.

