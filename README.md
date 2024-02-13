[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OpenSenseAction/OS_data_format_conventions/HEAD)

# OpenSense data format conventions
In this repository specifications as well as code and example files to illustrate standard data formats and naming conventions derived from the [OpenSense Action](https://opensenseaction.eu/) 
are collected.    

## NetCDF specifications of CML, SML, and PWS
This repository holds netCDF_specifications stored in AsciiDoc format.

The motivation is to:
- Manage updates using standard Git procedures
- Enable versioning and version releases
- Enable presentation of new versions of OS conventions in a human readable form (either through GitHub, or Action website, or a pdf document)
- Possibly enable parsing of specifications by OS netCDF libraries

The form of specifications is inspired by  https://github.com/cf-convention/cf-conventions, however, at this point our approach is less complex and we aim at more lightweight functionality and conectivity to other tools.

## AsciiDoc format
AsciiDoc format is a plaintext format which is easy to write and easy to parse. There are many tools to convert it to other formats such as html or pdf and GitHub can automaticaly preview it. 

## Usage
Preview adoc files on GitHub webpagesite or fork it/download it and open it in any plain text editor.

#### Data
We use the [OpenMRG dataset](https://doi.org/10.5194/essd-14-5411-2022) as CML example data and PWS data from a dataset of [Amsterdam and the 
Netherlands](https://data.4tu.nl/articles/dataset/Rainfall_observations_datasets_from_Personal_Weather_Stations/12703250). Example notebooks show how to bring these datasets into the proposed data formats. This accompanies a white paper on standards and convetions for opportunisitic sensor data which can be found here: [to be released ...](https://opensenseaction.eu/)

#### Usage
You can easily explore the datasets and the transformation by clicking on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OpenSenseAction/OS_data_format_conventions/HEAD)
