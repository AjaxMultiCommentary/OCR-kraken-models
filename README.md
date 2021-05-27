# OCR kraken models

This repository contains pre-trained Kraken models for the OCR of historical classical commentaries. These models were trained on ground truth (GT) data from two sources: 
1. the [OCR GT for Historical Commentaries](https://github.com/AjaxMultiCommentary/GT-commentaries-OCR) dataset (\# of lines)
2. the [Polytonic Greek Training Data fromHistoric Texts (Pogretra)](https://doi.org/10.5281/zenodo.4774200) dataset v1.0 (\# of lines).

For detailed information about each model, please refer to the `metadata.json` file contained in the model's directory.

## Models

| Name  | Description | Line Example |
| ------------- | ------------- | ------------- | 
| `greek-english_porson_sophoclesplaysa05campgoog`  | Model based on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s `XYZ.mlmodel` and enhanced with training materials coming from Jebb's commentary.  | ![](./example-snippets/sophoclesplaysa05campgoog_0177_19.png) |
`greek-german_serifs_sophokle1v3soph`  | Model for German commentaries typeset with serifs font. It is based on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s `german-serifs-2021-03-21-22-05-18_best.mlmodel`, enhanced with materials coming from Schneidewin's commentary.  |![](./example-snippets/sophokle1v3soph_0140_44.png)
| `greek-german_serifs_bsb10234118`  | Model for German commentaries typeset with serifs font. It is based on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s  `german-serifs-2021-03-21-22-05-18_best.mlmodel`, enhanced with materials coming from Lobeck's Latin commentary.   | ![](./example-snippets/bsb10234118_0090_4.png)

## Acknowledgements

Data in this repository were produced in the context of the Ajax Multi-Commentary project, funded by the Swiss National Science Foundation under an Ambizione grant [PZ00P1\_186033](http://p3.snf.ch/project-186033).

Contributors: Bruce Robertson (Mount Allison University), Sven Najem-Meyer (EPFL), Matteo Romanello (UNIL).