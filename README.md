# PhD Applicant Task

Here is a short Python + Materials Science task for candidates interested in joining the D2R2 group. 
With basic knowledge in Python and Materials Science this should be achievable in about 1 hour.

## Getting Started

1) Download this repository. 
2) Use the `template.py` file to write your Python code in.


## Task A (Python and Databases)

1) Download the following database: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10381506.svg)](https://doi.org/10.5281/zenodo.10381506)
2) Move the file `WF-CE_database_58332.json` into the repository folder.
3) Write Python code to plot the distribution of column `cleavage_energy` (save the created plot as a png or pdf file).
4) Are the columns `WF` and `Fermi` correlated? Write code to assess their correlation.

## Task B (Materials Informatics)

1) Install `pymatgen`.
2) Write a function that takes any pymatgen `Structure` object and returns 
the unit cell volume, number of unique chemical elements, and the angle between 
lattice vectors *a* and *b*. 
3) Get the crystal structure `mp-2490` from the Materials Project.
4) Load that structure with pymatgen.
5) Test the function from step 2 with the loaded structure.

## Task C (Answer Questions)

There are a 4 short questions in file `questions.txt`. Please, add your answers to the same file.

## Submission

Please, create one file `submission.zip` containing all the files (`template.py` containing your code, 
`questions.txt` containing your answers, and the plot you created as png/pdf) and 
send it to me via email. Thank you!

