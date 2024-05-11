# SCOP
Predicting classes of protein sequences

We are planning to develop a Structural Classification of Protein Sequences (SCOP) application. The main purpose of this project is to predict the classes of given protein sequences. The SCOP app will be used to predict the class of a given protein sequence, which will be provided in the form of a PDB ID or PSSM file. We aim to predict the top level of SCOP hierarchical classification (Protein fold classes), which is further classified into folds, superfamilies, and families.

A motivation for this classification is to determine the evolutionary relationship between proteins. Proteins with the same shapes but little sequence or functional similarity are placed in different superfamilies and are assumed to have only a very distant common ancestor. Proteins having the same shape and some sequence and/or functional similarity are placed in "families," and are assumed to have a closer common ancestor. This represents the top-level "root" of the SCOP hierarchical classification.

Conclusion

The broadest groups in SCOP are the protein fold classes. These classes group structures with similar secondary structure compositions but different overall tertiary structures and evolutionary origins. This represents the top-level "root" of the SCOP hierarchical classification.

The project is developed using the Python language and Flask. We implemented this project in Google Colab. We can predict up to 4 classes:

All alpha proteins: Domains consisting of α-helices
All beta proteins: Domains consisting of β-sheets
Alpha and beta proteins (a/b): Mainly parallel beta sheets (beta-alpha-beta units)
Alpha and beta proteins (a+b): Mainly antiparallel beta sheets (segregated alpha and beta regions)
After performing various comprehensive tests, we conclude that our project is functioning correctly. However, there is always room for improvement and learning. This was our first ML project, and indeed, we learned something new from it. We are now looking forward to overcoming the existing limitations and adding new possible extensions, which are discussed in the next section.

Project report for this SCOP application
https://github.com/PrincyGajera/SCOP/blob/main/Docs/Project_Report.pdf
