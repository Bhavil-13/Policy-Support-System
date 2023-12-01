
# Policy Support System - WSL

This initiative entails the development of a system dedicated to the generation of case files and the creation of stability modeling visualizations on Tableau.


## Stability Modelling

The PIA files are utilized as input data for the Stability Modeling code. The code systematically processes these files, extracting stress values, and then proceeds to aggregate the data according to talukas, organized on a district-wide basis.


### My Contribution

1. Identified and resolved errors in the original code through systematic troubleshooting.
2. Rectified the graph generation process to eliminate extraneous edges and ensure the accuracy of the visual representation.
3. Expanded the functionality of the code to support both 2D and 3D graph representations.
4. Implemented a district-wise aggregation of talukas, enhancing the granularity of data analysis.
5. Produced Excel files containing impact versus stability values for all districts within the Karnataka region, facilitating comprehensive and organized data presentation.

### How to run

Simply go to the 2D and 3D stress mapping files inside notebooks folder, and click run all in the notebooks. You will get all the output files in the output folders.

1. The 2D code necessitates the inclusion of IMR and MMR parameters.
2. The 3D code requires the incorporation of IMR, MMR, and PAW parameters.
3. The creation of graph required the Adjecency file.
4. Execute the notebook sequentially to initiate the processing, resulting in the generation of the requisite files.


## Case Files

### About Case Files
1. The 1st case file comprises indicators and their respective identification codes.
2. The second case file encapsulates parameters, R-square values, and p-values associated with the linear regression line.
3. The third case file encapsulates parameters, R-square values, and p-values associated with the multiple linear regression line.

### My Contribution

I developed the case file generators and generated three distinct case files corresponding to different intervention scenarios.
