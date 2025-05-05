Title: Python-assignment

Data Loading:

Parsed penguins_cytb.fasta to extract DNA sequences using BioPython.

Loaded species mass data from penguins_mass.csv into a Pandas DataFrame.

Sequence Translation:

Implemented a manual DNA-to-protein translation function using the Vertebrate Mitochondrial Codon Table.

Computed Values:

Molecular Weight: Calculated for each translated protein using BioPython’s Protein Analysis.

GC Content: Calculated the percentage of G and C nucleotides in each DNA sequence.

Sequence Length: Measured the length of each cytochrome-b sequence.

Data Integration:

Added computed values (molecular_weight, GC_content, sequence_length) into the existing DataFrame.

Visualization:

Created multiple plots to summarize and explore the data.

Graph Interpretation:
1. Adult Body Mass per Penguin Species
This bar chart compares the average adult mass of each penguin species.

 Observation: The smallest penguin species is Eudyptula minor, commonly known as the Little Blue Penguin or Fairy Penguin.

2. Molecular Weight vs GC Content
A scatter plot showing the relationship between GC content and the molecular weight of translated proteins.

Observation: There doesn’t seem to be a strong linear relationship, suggesting molecular weight isn’t directly dependent on GC content.

3. Correlation Heatmap
A heatmap of correlation coefficients among mass, molecular_weight, GC_content, and sequence_length.

Observation: Useful for identifying trends, such as potential relationships between body size and genomic properties.

4. Pairplot
A multi-dimensional scatter plot matrix to examine distributions and relationships among the variables.

Observation: Highlights possible clustering patterns or outliers in the data.

5. Cytochrome-b Sequence Length per Species
Bar chart showing the length of DNA sequences per species.

 Observation: All sequences are roughly similar in length, confirming consistency in alignment and sequencing.
