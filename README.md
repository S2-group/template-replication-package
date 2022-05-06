# Thesis / Paper Title
This repository is a companion page for the following thesis / publication:
> Author Names. Publication year. Thesis / Paper title. Publication venue / proceedings.

It contains all the material required for replicating the study, including: X, Y, and Z.

## How to cite us
The scientific article describing design, execution, and main results of this study is available [here](https://www.google.com).<br> 
If this study is helping your research, consider to cite it is as follows, thanks!

```
@article{,
  title={},
  author={},
  journal={},
  volume={},
  pages={},
  year={},
  publisher={}
}
```

## Quick start
Here a documentation on how to use the replication material should be provided.

### Getting started

1. Provide step-by-step instruction on how to use this repository, including requirements, and installation / script execution steps.

2. Code snippets should be formatted as follows.
   - `git clone https://github.com/S2-group/template-replication-package`

3. Links to specific folders / files of the repository can be linked in Markdown, for example this is a link to the [src](src/) folder.

## Repository Structure
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
* a [src](src/) folder, containing the entirety of the source code used in the study,
* a [data](data/) folder, containing the raw, intermediate, and final data of the study
* if needed, a [documentation](documentation/) folder, where additional information w.r.t. this README is provided. 

In addition, the replication package can include additional data/results (in form of raw data, tables, and/or diagrams) which were not included in the study manuscript.

## Replication package naming convention
The final name of this repository, as appearing in the published article, should be formatted according to the following naming convention:
`<short conference/journal name>-<yyyy>-<semantic word>-<semantic word>-rep-pkg`

For example, the repository of a research published at the International conference on ICT for Sustainability (ICT4S) in 2022, which investigates cloud tactics would be named `ICT4S-2022-cloud-tactics-rep-pkg`

## Preferred repository license
As general indication, we suggest to use:
* [MIT license](https://opensource.org/licenses/MIT) for code-based repositories, and 
* [Creative Commons Attribution 4.0	(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) for text-based repository (papers, docts, etc.).

For more information on how to add a license to your replication package, refer to the [official GitHUb documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository).
