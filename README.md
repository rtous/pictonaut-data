## Description

This repository contains the PICTONAUT-DATA dataset, consisting of ....

A deep convolutional neural network, called UPC-UCV, for P-wave earthquake detection and source region estimation over this dataset can be found [here](https://github.com/rtous/deepquake).

## Files

 The data (both the files with the waveforms and the metadata) comes from [SEISAN](https://www.geosig.com/files/GS_SEISAN_9_0_1.pdf), a seismic analysis software suite.

### Metadata (catalog)

The analyst-labeled P-wave arrivals related to the 949 earthquakes can be found in different formats:

* JSON format (catalog.json)
* Nordic format in several files (sfiles_nordicformat directory)
* Nordic format in one file (arrival_times.txt)
* Raw SEISAN files (original data also in Nordic format)

Just pick one of the alternatives as they contain the same information. 


### Waveforms (.mseed files)

The waveforms containg the P-arrivals of the earthquakes can be found in the "mseed" folder:

* Each .mseed file contains three channel waveforms in miniSEED format and sampled at 100Hz.
* Each .mseed file contains waveforms from just one station.

## Acknowledgements

If you find this repository useful for your research, please cite the original publication:


	@article{Tous2020,
	    author = {R. Tous and L. Alvarado and B. Otero and L. Cruz and O. Rojas},
	    title = {Deep Neural Networks for Earthquake Detection and Source Region Estimation in North Central Venezuela},
	    journal = {Bulletin of the Seismological Society of America},
	    number = {?},
	    pages = {?--?},
	    volume = {?},
	    year = {2020}
	}