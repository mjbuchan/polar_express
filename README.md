# polar_express
Akerman Lab - Cortical neuron polarity (but faster)

All aboard the calculating normalised polarity vectors from histograms express.

![The_Polar_Express_(2004)_poster](https://user-images.githubusercontent.com/28899028/106398382-585ef200-640a-11eb-8399-e50aa7a08ae5.jpg)

## What is this for?

There are lots of ways for calculating polarity of dendrites (most are vectorised, slow and gross) - this is another... also a thinly veiled excuse for memes.

### How does it work? 

* Takes output from MBF Neurolucida (currently updating for FIJ) - designed for wedge analysis (i.e. centred on the soma) but would work equally well for other polarity measures.
* Turns every histogram bin into a vector 
* Averages across bins and normalises to output a "normalised polarity vector" (this can then be used to calculate scalar projections with respect to anatomical landmarks, or just x/y directions)

#### To do

* Add projection functions 
* Troubleshoot for different platforms (i.e. FIJI) - help welcome!
