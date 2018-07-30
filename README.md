# Global Maps of Potential Natural Vegetation at 1 km resolution

Summary: This repository contains R code and some outputs of spatial predictions related with the production of [Global Maps of Potential Natural Vegetation at 1 km resolution](https://www.arcgis.com/apps/MapJournal/index.html?appid=1856322400844a7cab348bccfa4bee76). Three case studies were considered: (1) global distribution of biomes based on the BIOME 6000 data set (8057 modern pollen-based site reconstructions), (2) distribution of forest tree species in Europe based on detailed occurrence records (1,546,435 ground observations), and (3) global monthly Fraction of Absorbed Photosynthetically Active Radiation (FAPAR) values (30,301 randomly-sampled points).

![alt text](https://github.com/envirometrix/PNVmaps/blob/master/img/Fig_global_biomes_map.png "Output predictions for global biomes.")

# Step-by-step tutorial

[This tutorial](https://github.com/Envirometrix/PNVmaps/tree/master/tutorial) explains how to fit models and produce predictions for smaller area in Europe. To run this tutorial you might need to install and customize some [R / OS GIS software](https://envirometrix.github.io/PredictiveSoilMapping/software.html).

*Please cite as:*

* Hengl T, Walsh MG, Sanderman J, Wheeler I, Harrison SP, Prentice IC. (2018) [**Global mapping of potential natural vegetation: an assessment of Machine Learning algorithms for estimating land potential**](https://doi.org/10.7287/peerj.preprints.26811v2). PeerJ Preprints 6:e26811v2 https://doi.org/10.7287/peerj.preprints.26811v2 (accepted for publication)

# Download Maps

All maps are available for download under the [Open Database License (ODbl) v1.0](https://opendatacommons.org/licenses/odbl/) and can be downloaded from http://dx.doi.org/10.7910/DVN/QQHCIK without restrictions.

# Disclaimer

This is the v0.1 of the Global Potential Natural Vegetation maps at 1 km. This data is preliminary and errors and artifacts are still possible. Training data sets BIOME 6000 and EU Forest are constantly being updated and could still contain erroneously geolocated points. Predictions of FAPAR are based on randomly simulated points and not on ground observations of FAPAR and classification of sites. Predictions of EU forest tree species are presented for experimental purposes only. To report an issue or artifact in maps, please use https://github.com/envirometrix/PNVmaps/issues.

