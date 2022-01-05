# **README for Variant Calling Pipeline for SARS-CoV-2 using Illumina short reads**

Parts of this pipeline approach are based on the pipeline described in the [Data Carpentry Genomics lessons](https://datacarpentry.org/genomics-workshop/), which are made available under a [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

Aavikumar Bhakta  
abhakta2@dons.usfca.edu  
November 14, 2021  

## Reasoning on why I want to work with the dataset I have chosen
For this project I want to work with SARS-CoV-2 data that comes out of Brazil because that is the location where the P.1 variant (gamma) evolved and went rampant throughout the country and then spread to the rest of South America and the world. I want to see how this variant affected the number of deaths and cases of COVID-19 in Brazil. For example, at what rate did it increase the daily cases and deaths? Brazil is also one of the most affected countries in the world and accounts for about 8.6% of total cases and about 12% of total deaths. It is the the third most affected country in the world which makes it interesting to study and analyze data from.

## Bioproject dataset information
* SRA Bioproject ID number: 752057
* This dataset contains 10.65 Gb of data and includes 185 runs.

## Outline on how I plan on analyzing the data
This dataset includes geographic locations in Brazil, collection dates, virus name, host age, host sex, and isolate. All of these different parameters will allow me to parse the data and categorize it in various ways to create different ways to analyze the data. I will clean up the column names to make the information more readable using tydr, and make the column data cleaner, such as the location data. Then categorize the columns to list the data from least to most and group the cells with the same data using tidyr. I will be creating bar plots using ggplot to find out whether there is any relationship between age and the virus, and host sex and the virus. I want to analyze the data from the different geographical regions within Brazil and see whether there is one area that had more cases than the others, and I will use ggplot to make a bar graph and density plot to visualize this data. If possible, I want to look at the SARS-CoV-2 sequencing data to see whether the sequence changed around January 2021 to a variation similar to that of P.1 (gamma variant).
