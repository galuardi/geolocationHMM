# geolocationHMM
A new method of geolocation from noisy light data using a hidden Markov model

As part of my Honours project I developed a new method of light-based geolocation that relies on the overall pattern of day and night,
rather than an explicit dependence on twilights as per the threshold or template-fit methods. For an introduction to geolocation
using recorded light, please see https://en.wikipedia.org/wiki/Light_level_geolocator
This repository holds important data for my thesis and a paper which is to be submitted detailing the 'twilight free' method.

Database:
86372_filteredGPS.csv     has the filtered GPS positions from the southern elephant seal example
TDR86372ds.csv            has the resampled light data from the southern elephant seal example

R Markdown files:
twilight free algorithm example ses   is an R markdown document which will download the data sets and produce a track from the noisy
                          light data, then compare the accuracy and precision of GLS-derived locations against GPS-derived locations.
twilight free algorithm example stsh  is an R markdown document which will download the data set and produce a track from simulated
                          noisy light data, then compare the accuracy and precision of GLS-derived locations against an average of
                          simulated daily locations
