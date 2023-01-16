**Top N LOF Outlier Detection [Reference Paper](http://hanj.cs.illinois.edu/pdf/kdd01.pdf)** 

# Instructions to download and run source codes
1. Source codes are stored in folder named "TopNLOFKDD-github"
2. In the lib folder, run the command "jar xf [filename].jar" for each of the 3 jar files.
In Java, you must compile the codes first before running for the first time or after editing the codes.
3. To compile the codes, navigate to TopNLOFKDD-github directory and run the command "javac -cp lib -sourcepath src -d lib src/microcluster/topnlof/TopNLOFDetection.java"
4. To run the codes, stay in the TopNLOFKDD-github directory and run the command "java -cp lib microcluster.topnlof.TopNLOFDetection -c 2 -d 2 -i data/accuracy/dimension_20.csv -k 2 -n 9000 -o data/accuracy_results/results_20 -r 2"
The command above is an example of how you can run the codes.

## Explanation of the parameters in Step 4
-cp is the class path where the java class files are stored. This class path will be fixed across all subsequent calls.
-c, -d, -k, -n, -r are the parameters of the algorithm. Please refer to lit_review/Lit Review pdf file for a more detailed explanation of these parameters.
-i is the directory of the input file
-o is the directory to store the output of the algorithm

# Project Structure
- TopNLOFKDD-github folder contains the source codes
- lit_review folder contains the documentation and codes for the Lit Review section
- lit_review_screenshots folder contains the screenshots used for the readme document in Lit Review section
- explore_source_code folder contains the documentation and codes for the Explore Source Code section
