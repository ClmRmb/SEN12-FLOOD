## SEN12-FLOOD Dataset

This dataset is composed of optical Sentinel 2 and SAR Sentinel 1 image sequences for the the detection of flooded areas.
It is available on the [IEEE dataport](https://ieee-dataport.org/open-access/sen12-flood-sar-and-multispectral-dataset-flood-detection).


### Overview

The SEN12-FLOOD Dataset is built from 336 time series containing Sentinel 1 and Sentinel 2 images of areas that suffered a major flooding event during the 2019 winter. The acquisition period goes from December 2018 to May 2019. The observed areas are clustered in East Africa, South West Africa, Middle-East and Australia. 
A sequence corresponds to several tiles of size 512x512 each of them corresponding to a crop of a given acquisition. The global characteristics are summed up in the following table:

| Number of sequences | Tile dimension | Locations | 
| ------------- |------------- | -----|
| 336 | 512x512 | West Africa, South East Africa, Middle-East, Australia |

## Sentinel 2 images

The Sentinel 2 satellites are a constellation of two polar-orbiting satellites, S2A and S2B, operated by ESA. A MultiSpectral Instrument (MSI) is embedded on each satellite providing wide-swath, high-resolution, multi-spectralimages with a high temporal sampling. The spectral characteristics are:

| Band name | Pixel Size | Wavelength |
| ------------- |------------- | -----------|
| B1 | 60 m | 443.9nm (S2A) / 442.3nm (S2B) |
| B2 | 10 m | 496.6nm (S2A) / 492.1nm (S2B) |
| B3 | 10 m | 560nm (S2A) / 559nm (S2B) |
| B4 | 10 m | 664.5nm (S2A) / 665nm (S2B) |
| B5 | 20 m | 703.9nm (S2A) / 703.8nm (S2B) |
| B6 | 20 m | 740.2nm (S2A) / 739.1nm (S2B) |
| B7 | 20 m | 782.5nm (S2A) / 779.7nm (S2B) |
| B8 | 10 m | 835.1nm (S2A) / 833nm (S2B) |
| B8A | 20 m | 864.8nm (S2A) / 864nm (S2B) |
| B9 | 60 m | 945nm (S2A) / 943.2nm (S2B)|
| B11 | 20 m | 1613.7nm (S2A) / 1610.4nm (S2B) |
| B12 | 20 m | 2202.4nm (S2A) / 2185.7nm (S2B) |

The Sentinel 2 images in the SEN12-FLOOD dataset come from the [Multimedia Satellite Task](http://www.multimediaeval.org/mediaeval2019/multimediasatellite/) of the [2019 MediaEval](http://www.multimediaeval.org/mediaeval2019/) workshop. They are provided with 
Level 2A atmospheric correction. On average, there are 9 Sentinel 2 images per sequence.

## Sentinel 1 images

The Sentinel 1 satellites are also a constellation of two polar-orbiting satellites, S1A and S1B, operated by ESA. Unlike the Sentinel 2 satellites,
the Sentinel 1 constellation provides radar imaging of the Earth. Synthetic Aperture Radar (SAR) images can be acquired in any illumination
or cloud cover condition giving potentially access to a bigger stack of images than with optical sensors. The images in the dataset are 
available in dual band VV+VH : 


| Band name / Polarization | Pixel Size | Wavelength | 
| ------------- |------------- | -----------------|
| VV | 10 m | 5.405GHz |
| VH | 10 m | 5.405GHz |

The images are provided with radiometric calibration and Range Doppler Terrain Correction using the shuttle-radar topographic mission digital elevation model.
For the constitution of the SAR dataset, all the available satellite orbits have been considered which result in an incidence angle variety and thus potential geometric distortions.
On average there are 14 images per sequence.



