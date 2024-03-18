# ProstateZones

This repository contains files to organize the files and ease the use of the ProstateZones dataset.
The ProstateZones dataset is a collection of segmentations of the prostatic zones and urethra corresponding to open-acess images from the PROSTATEx dataset. The dataset is intended for research purposes in the field of medical imaging, particularly focusing on automatic segmentations of the prostate, prostatic zones, and urethra.




## Usage
The files in this repository are structured to facilitate organization and utilization of the ProstateZones dataset.

### Download ..

#### Images
The images can be downloaded from the Cancer Imaging Archive (TCIA) at the following link: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=23691656
#### Segmentations
The segmentations are available on Zenodo, accessible through the DOI: 10.5281/zenodo.10718469

### ProstateZones Dataset Folder Structure:

When the images and segmentations are downloaded ...
The 'data_to_folders' Python script arranges the images and their corresponding segmentations for easier access and management, according to the following structure:

- **Images**
  - ProstateX-0000
    - _adc-0000_
    - _cor-0000_
    - _dwi-0000_
    - _hbv-0000_
    - _sag-0000_
    - tra-0000
  - ProstateX-0007
  - ...

- **Train**
  - ProstateX-0000
    - _adc-0000_
    - _hbv-0000_
    - tra-0000
    - Seg-0000.nrrd
  - ProstateX-0008
  - ...

- **Validate**
  - ProstateX-0007
    - _adc-0007_
    - _hbv-0007_
    - tra-0007
    - Seg-0007.nrrd
  - ProstateX-0010
  - ...

- **Test**
  - ProstateX-0015
    - _adc-0015_
    - _hbv-0015_
    - tra-0015
    - Seg-0015_R1.nrrd
    - Seg-0015_R2.nrrd
  - ProstateX-0019
  - ...



### Evaluation Workflow
The evaluation workflow used to analyze the inter-reader variability data is included in this repository.
To run the evaluation workflow, you'll need Hero, a software tool for medical image analysis. You can sign up for a free trial at their webpage: https://www.heroimaging.com/

#### Setup for Hero
To set up the data for running the workflow in Hero, watch the provided videos on loading data and batching. These videos will guide you through the process of configuring Hero to work with the ProstateZones dataset.


## ... Additional Information ...
Dataset paper:

For more information about the dataset, see the DataDescriptor publication:

....

Citation
If you use this dataset in your work, please cite it as:

[insert citation here]
