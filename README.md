## `Description`

Here, we provide a tutorial how to assemble contigs from a metagenome.

An html for the tutorial can be found [here](https://ndombrowski.github.io/Assembly_tutorial/).

Files to follow this tutorial can be downloaded via zenodo and links are provided in the html.

The goal of this tutorial is to: 

- take the raw reads from 3 "mini-metagenomes" that were recovered from 3 depth profiles of the water column (500 m, 1000 m and 2000 m water depth )
- check the quality of the metagenoems
- do quality cleaning
- assemble the data using megahit and metaspades
- get the basics stats to characterize the assemblies.

The reason why we work with 3 metagenomes is because another pipeline that can follow the assembly is the binning pipeline. 

Most binning tools take into account coverage information, which make use of having data from several metagenomes (i.e. depth profiles in our case) 
and this tutorial will give an example how to run the code for a single metagenome or in a loop with all metagenomes of interest.

The example material to follow the tutorial can be found [here](https://zenodo.org/record/7752831#.ZBhiotDMJD8)


## `Cite`

Additionally, if you found this tutorial useful and use it in your work and you reuse some of the code feel free to link to this repository to your methods section.
