# geolocationHMM
A new method of geolocation from noisy light data using a hidden Markov model

As part of my Honours project I developed a new method of light-based geolocation that relies on the overall pattern of day and night,
rather than an explicit dependence on twilights as per the threshold or template-fit methods. For an introduction to geolocation
using recorded light, please see https://en.wikipedia.org/wiki/Light_level_geolocator<br><br>
This repository holds important data for my thesis and a paper which is to be submitted detailing the 'twilight free' method.<br>

*Database:*<br>
**86372_filteredGPS.csv**   filtered GPS positions from the southern elephant seal example<br>
**TDR86372ds.csv**            resampled light data from the southern elephant seal example<br>
**noisy_stsh.csv**            BAStag format simulated noisy light data for the short-tailed shearwater example<br>
**perfect_stsh.csv**         BAStag format simulated perfect light data for the short-tailed shearwater example<br>
**018_WI_OCT2012estelleSST.csv**    track from SGAT which was the template for noisy_stsh and perfect_stsh<br><br>

*R Markdown files:*<br>
**twilight free algorithm example ses**   R markdown document which will download the data sets and produce a track from the noisy
                          light data, then compare the accuracy and precision of GLS-derived locations against GPS-derived locations. Download and open in R studio.<br>
                          
*Other files:*<br>
**twilight_free_algorithm_example_ses.html**  output file for the impatient
