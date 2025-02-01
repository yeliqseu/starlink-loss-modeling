@[TOC](Data and script usage instructions)
This repository provides the data of the WCNC 2025 paper (Modeling Packet Loss of Low-Earth Orbit Satellite Networks) and the associated Matlab script; Follow these steps to quickly reproduce the experiments in the article. 

### Starlink Data
Starlink measurement data are stored at the following link:
[ https://pan.baidu.com/s/1YS2oQYTGggvkuz2WxZU0bQ Extract code: wah1].
In the downloaded data, 'loss' is the packet loss data and 'arrivals' is the packet loss arrival interval data.

### MAP Toolbox (Butools)
The numerical script uses Butools for MAP modeling. Please download the butools's Matlab package from [https://github.com/ghorvath78/butools](https://github.com/ghorvath78/butools) and unzip it into the script folder.

### Reproduce Results
Make sure that the Starlink data, the Butools toolbox folder, and the GAN-generated data are placed in the same folder. Run *modeling.mlx* in Matlab to reproduce the results of the paper. Carefully rename paths to the data files in the script if necessary.

