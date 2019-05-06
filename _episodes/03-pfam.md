---
title: "Using Pfam to Predict Protein Function"
teaching: 10
exercises: 60
questions:
- "How can a protein family be identified from its structure?"
objectives:
- "Students will identify the acceptable syntax and the type of searches that can be done with that format to identify related Pfam superfamilies."
- "Students will identify additional links on the Pfam site that provide insights into the function of their proteins."
- "Students will distinguish the terms “family”, “superfamily” and “domain” as they are used in Pfam."
- "Students will identify the most highly conserved amino acid residues in their protein of interest."
- "Students will correlate protein sequence and protein function."
- "Students will identify the limitations of the results provided by Pfam."
- "Students will integrate Pfam results with results from other bioinformatics tools."
- "In combination with all of the bioinformatics tools, students will hypothesize a function for their protein structure."
keypoints:
- "Highly conserved amino acid residues does not guarantee similarity in function."
---
<img src="../fig/pfam.png" alt="Pfam" width="100" style="float: left; margin-top: 0px; margin-right: 10px" />
Pfam (“Protein Families”) is a database that groups proteins into evolutionarily related families based on sequence.  Pfam contains over 15,000 families, where each family is defined by a a set of representative members sharing a common “seed” sequence.  A family’s shared sequence is displayed as a Hidden Markov Model (HHM) logo, which presents defining sequence as stacked single-letter amino acids.  Thus, a Pfam search differs from a BLAST search in that Pfam preferentially searches for matches between the query sequence and the seed sequences that define the HHM.  When a user searches the Pfam database, the result displays known families to which the user’s query sequence matches.  Often, a query sequence may belong to more than one family, particularly if the query protein contains multiple structural domains.  In this manner, a Pfam search can give the user information about both the structural domains into which a protein is likely to fold, and the evolutionary homologs with which it many share function. Students are encouraged to view their results from Pfam as information to be integrated with results from other computational and wet lab approaches to narrow the focus of their prediction of protein function.
<br/><br/><br/>

> ## Module Resources
>[Download student module here](https://docs.google.com/document/d/1Z5SyXlp7FL020IubvA482UvQZcsLoiVqBuQ2xJ-5c2s/edit?usp=sharing)
{: .callout}
