# Social factors Data

The Social factors database contains social information for societies held within the Global Jukebox project. 

This repository is for pulling, formatting, validating and cleaning the Social factors dataset.

Data is presented in three data tables within raw/

| file             | description                                              |
|------------------|----------------------------------------------------------|
| data.csv         | Codings on the social factors of a society               |
| sources.csv      | Information on where data was sourced for each society   |
| societies.csv    | Metadata on the societies from which the songs originate.|


## Getting started

To see the list of available commands and scripts type into your terminal:

`make help`

<small><strong>Note:</strong> This code has been tested for Mac/Windows, but if you are on a windows, please submit a pull request so we can make it easier to run. This step assumes you have a working distribution of `make`. For installation instructions please update XCode or follow the specific guidelines for installing `make` on your system. </small>

## Collect google drive data

`make download`
