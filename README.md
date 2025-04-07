# TCN-GAN
Replication and modification of QuantGAN to generate financial time series that captures major stylized facts like Fat Tails, Volatility Clustering and Leverage Effect. 

Data used:  S\& P 500 index Jan 2009 - Dec 2019

Implementations:
1. Tensorflow Non-Causal TCN GAN
2. PyTorch Non-Causal TCN GAN (pytorch version of 1.)
3. PyTorch Causal TCN GAN (replication of QuantGAN)
4. GARCH(1,1) (Baseline)


Reference Code and Papers:
- [QuantGAN2019](https://arxiv.org/abs/1907.06673)
- [RCont2001](http://rama.cont.perso.math.cnrs.fr/pdf/empirical.pdf)
- [ICascha](https://github.com/ICascha/QuantGANs-replication)
- [PakAndrey](https://github.com/PakAndrey/QuantGANforRisk)
- [JamesSullivan](https://github.com/JamesSullivan/temporalCN/tree/main)
- [TCN](https://github.com/locuslab/TCN)
