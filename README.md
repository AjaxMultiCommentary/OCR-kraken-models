# OCR kraken models

This repository contains pre-trained Kraken models for the OCR of historical classical commentaries. These models were trained on ground truth (GT) data from two sources: 
1. the [Polytonic Greek Training Data from Historic Texts (Pogretra)](https://doi.org/10.5281/zenodo.4774200) dataset v1.0 (31,972 lines)
2. the [OCR GT for Historical Commentaries](https://github.com/AjaxMultiCommentary/GT-commentaries-OCR) dataset (3,356 lines)

For detailed information about each model, please refer to the `metadata.json` file contained in the model's directory.

## Models

| Name  | Description | Line Example |
| ------------- | ------------- | ------------- | 
| [greek-english_porson_sophoclesplaysa05campgoog](kraken-models/greek-english_porson_sophoclesplaysa05campgoog/greek-english_porson_sophoclesplaysa05campgoog.mlmodel)  | Model trained on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s Porson data, enhanced with additional training materials from Jebb's commentary.  | ![](./example-snippets/sophoclesplaysa05campgoog_0177_19.png) |
[greek-german_serifs_sophokle1v3soph](kraken-models/greek-german_serifs_sophokle1v3soph/greek-german_serifs_sophokle1v3soph.mlmodel)  | Model trained on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s German-serifs data, enhanced with additional training materials from Schneidewin's commentary.  |![](./example-snippets/sophokle1v3soph_0140_44.png)
| [greek-german_serifs_bsb10234118](kraken-models/greek-german_serifs_bsb10234118/greek-german_serifs_bsb10234118.mlmodel)  | Model trained on [Pogretra](https://doi.org/10.5281/zenodo.4774200)'s  German-serifs data, enhanced with additional training materials from Lobeck's Latin commentary.   | ![](./example-snippets/bsb10234118_0090_4.png)

## Acknowledgements

Data in this repository were produced in the context of the Ajax Multi-Commentary project, funded by the Swiss National Science Foundation under an Ambizione grant [PZ00P1\_186033](http://p3.snf.ch/project-186033).

Contributors: Bruce Robertson (Mount Allison University), Sven Najem-Meyer (EPFL), Matteo Romanello (UNIL).