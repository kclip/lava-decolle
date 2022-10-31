# DECOLLE

Deep Continuous Local Learning (DECOLLE) is a surrogate gradient (SG) 
algorithm leveraging per-layer local errors for online learning of 
deep SNNs, for which details can be found in reference
[Kaiser et al., 2020](https://www.frontiersin.org/articles/10.3389/fnins.2020.00424/full). 

Each layer of the SNN is associated to a fixed, random projection layer
to compute the real-valued errors.

This library is meant as an add-on to Intel's [Lava](https://github.com/lava-nc) framework. 
It is based on the authors' own implementation, which can be found on
their [GitHub repository](https://github.com/nmi-lab/decolle-public/tree/master). 


## Dependencies
`lava-dl` library (https://github.com/lava-nc/lava-dl/)

## Getting Started
[NMNIST digit classification](https://github.com/kclip/lava-decolle/blob/main/tutorials/lava/lib/dl/decolle/nmnist/train.ipynb) tutorial

[Comparison with SLAYER](https://github.com/kclip/lava-decolle/blob/main/tutorials/lava/lib/dl/decolle/nmnist/slayer_comparison.ipynb)


## License

This project is licensed under the GPLv3 License - see the [LICENSE.txt](LICENSE.txt) file for details

### Author
Nicolas Skatchkovsky ([nskat](https://github.com/nskat))