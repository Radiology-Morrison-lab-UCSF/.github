# Morrison Lab 

Herein are Git repositories for Melanie Morrison's Lab at the University of California, San Francisco.

## Public

Most code has limited public visibility. If you wish to collaborate or access any non-public code please [contact Dr Morrison](https://profiles.ucsf.edu/melanie.morrison).

For more information on our Lab, please [visit our webpage](https://morrisonlab.ucsf.edu/).

## Lab Member Instructions

By default, create new repositories with `Internal` access. Give repositories a unique and distinguishable name, and a README.md file. The README must state what your code does, any dependencies it relies upon, and how to run it.

### Protected Health Information 
Remember that PHI must not end up in git *regardless as to privacy settings*. Beware in particular of committing results or filepaths containing participant PHI. 

If PHI does end up in git, contact a senior lab member to ensure it is removed fully from your project history. It is not sufficient to simply correct a file and recommit as old commits can still be browsed.

Discuss with a senior lab member if you feel have no choice but to embed PHI in your code _before_ committing that code. There is likely a better solution. If not, an alternative repository location will need to be sought.

### Non-Text Files

Ensure that binary files, such as images, are either not committed or are committed using LFS. If your code has dependencies that may not be accessible in the future (such as resources hosted on external University Websites) opt to utilize LFS to ensure longevity of your work. If dependencies are in a 'permanent' repository elsewhere, consider writing an installation script to fetch them (e.g. using `wget` or `apt-get`) instead.
