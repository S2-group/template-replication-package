# Thesis / Paper Title
This repository is a companion page for the following thesis / publication:
> Author Names. Publication year. Thesis / Paper title. Publication venue / proceedings.

It contains all the material required for replicating the experiments, including: X, Y, and Z.

Quick start
---------------
Here a documentation on how to use the replication material should be provided.

### Getting started

1. Provide step-by-step instruction on how to use this repository, including requirements, and installation / script execution steps.

2. Code snippets should be formatted as follows.
   - `git clone https://github.com/S2-group/template-replication-package`

3. Links to specific folders / files of the repository can be linked in Markdown, for example this is a link to the [src](src/) folder.

Repository Structure
---------------
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |
     |--- src/                             Source code used in the thesis / paper
     |
     |--- documentation/                   Further structured documentation of the replication package content
     |
     |--- data/                            Data used in the thesis / paper 
            |
            |--- additional_subfolder/     Subfolders should be further nested to increase readability                 
  

Usually, replication packages should include:
* a [src](src/) folder, containing the entirety ofnthe source code used in the study,
* a [data](data/) folder, containing the raw, intermediate, and final data of the study
* if needed, a [documentation](documentation/) folder, where additional information w.r.t. this README is provided. 

In addition, the replication can include additional data / results (in form of raw data, tables, and/or diagrams) which were not included in the study manuscript.
