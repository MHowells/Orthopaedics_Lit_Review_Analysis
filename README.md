# A Systematic Review of OR/MS Methods Applied to Orthopaedic Care Settings and Treatments

## Overview

This is a repository of all the data and analysis code to reproduce all the 
plots and analysis for the paper ['Fractured systems: a literature review of 
OR/MS methods applied to orthopaedic care settings and treatments.'](https://doi.org/10.1080/20476965.2023.2264348) [1].

This repository is structured as follows:

```
LitReviewAnalysis/
	|--README.md	
	|--requirements.txt
	|--LiteratureTaxonomy.csv
	|--Analysis.ipynb
	|--plots/
		|--YearPublished.pdf
		|--JCRCategory.pdf
		...
```

To reproduce all plots in the paper, we used Python 3.9.7, install all the 
requirements in `requirements.txt`,open `Analysis.ipynb` and run every cell in 
order.

The file 'LiteratureTaxonomy.csv' contains information on the 492 papers 
analysed in the paper.

## Installing Dependencies

The model is written in Python 3.9.7, with the requirements in requirements.txt.

To create a virtual environment:

    $ python -m venv env

To start using the new virtual environment:

    $ source env/bin/activate

To install the dependencies:

    $ python -m pip install -r requirements.txt

## Author ORCID

- Matthew Howells: [0000-0002-3931-7027](https://orcid.org/0000-0002-3931-7027)
- Paul Harper: [0000-0001-7894-4907](https://orcid.org/0000-0001-7894-4907)
- Geraint Palmer: [0000-0001-7865-6964](https://orcid.org/0000-0001-7865-6964)
- Daniel Gartner: [0000-0003-4361-8559](https://orcid.org/0000-0003-4361-8559)

## Citation

> Matthew Howells, Paul Harper, Geraint Palmer, & Daniel Gartner. (2023). Data 
and analysis for orthopaedics literature review. (Version 1) [Data set]. Zenodo. 
https://doi.org/10.5281/zenodo.7995520

```bibtex
@dataset{matthew_howells_2023_7995520,
  author       = {Matthew Howells and
                  Paul Harper and
                  Geraint Palmer and
                  Daniel Gartner},
  title        = {Data and analysis for orthopaedics literature
                   review.
                  },
  month        = feb,
  year         = 2023,
  publisher    = {Zenodo},
  version      = 1,
  doi          = {10.5281/zenodo.7995520},
  url          = {https://doi.org/10.5281/zenodo.7995520},
}
```

## Funding 

This code is funded by an Engineering and Physical Sciences Research Council 
(EPSRC) Enhanced CASE PhD Studentship with Cardiff and Vale University Health 
Board as the project partner.

## References

<a id="1">[1]</a> 
Howells, M., Harper, P., Palmer, G., & Gartner, D. (2024).
Fractured systems: a literature review of OR/MS methods applied to orthopaedic 
care settings and treatments. 
Health Systems, 13(3), 151-176.