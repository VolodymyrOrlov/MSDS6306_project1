# The Beers Project
Chew Swee, Mwangi Julius, Orlov Volodymyr

## Introduction
This project contains source code supporting analysis of International Bitterness Units_ (IBU) and _Alcohol by Volume_ (ABV) of beers across the United States. The goal of the project is to look at and describe certain aspects of this alcoholic drink, including: 

* Statistical characteristics of ABV and IBU across the country
* Relationship between alcoholic content and bitterness

## Data

The dataset consist of 2 files, contains 558 unique breweries and 2305 distinct beers. Each beer in the _beers_ dataset is described by name, id, alcoholic content and bitterness, style and ounces. Each brewery is described by name, id, city and state.

## Code structure

Our analysis and colclusion is summarized in the *report.rmd* file. Data can be found in the *data* folder. To compile the report to _HTML_ format please run following command line script from the root folder of the project:

```
$ ./compile_report.r
```