# eJTK analysis

## Setup
Clone the repository and set up the directories "Proteome" and "Phosphoproteome", and within each have the directories "Combined" and "Independent". Tab-separated files are provided by the "1 Normalising Data" R notebooks for the respective datasets, and copied in.

Follow the instructions in the original README.md file to compile the code and test it using the provided example.

## My command

The command below was used for WT proteome combined analysis. The -x flag was not used for simplicity.

    ./eJTK-CalcP.py -f Proteome/Combined/WTeJTKcomb.txt -w ref_files/waveform_cosine.txt -p ref_files/period24.txt -s ref_files/phases_00-21_by3.txt -a ref_files/asymmetries_03-21_by3.txt
