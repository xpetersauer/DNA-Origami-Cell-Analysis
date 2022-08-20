# Analyze your DNA Origami Distribution on Your Cell Microscopy Images
This repository was my Spring 2022 Project: A Data Visualizer for DNA Origami Distribution for Non-expert audiences.

# Acknowledgements:
I'd like to thank current PhD candidate Weitao Wang and Professor Rebecca Taylor of the Microsystems and Mechanobiology Lab (MMBL) at Carnegie Mellon University (CMU) for advising and guiding me throughout this project.

The algorithm for my code is lightly inspired by the method for analyzing Receptor Dynamics in G-Coupled Protein Receptors (GCPRs):

Aymerich, María S et al. “Real-time G-protein-coupled receptor imaging to understand and quantify receptor dynamics.” TheScientificWorldJournal vol. 11 (2011): 1995-2010. doi:10.1100/2011/690858 [ResearchGate](https://www.researchgate.net/publication/51834317_Real-Time_G-Protein-Coupled_Receptor_Imaging_to_Understand_and_Quantify_Receptor_Dynamics)

# Sample Images Provided
The cell images used for this project are provided, if you are interested in running this code.

# How to Use the Code:
1. Download the file
- If you plan on uing the sample images, download these as well
2. Edit the filepath/directory containing your images
3. Run all the cells
- You may need to edit for "undefined value" errors if you plan on modifying this code, as it was primarily intended solely for my use

# Disclaimer
While the project intended on quantifying patchiness by comparing average intensities to a uniform distribution, this method is not complete in quantifying patchiness, as comparing the distribution of DNA Origami to a uniform distribution cannot exemplify topological shape of the distribution. A better method would be to compare the image via a power-law clustering method to analyze the image analogously to a scale-free-network.

