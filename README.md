# Electron_Liquid

This repository contains the ab initio path integral Monte Carlo results published in Phys. Rev. B (...), https://arxiv.org/abs/1911.07598

All results have been obtained for N=66 unpolarized electrons, except for (rs=20,theta=0.5), where we have N=20, and (rs=30,theta=0.5), where we have N=34.


The files "Response_rs_ theta_ .txt" contain data for the static density response with the following key:
1) q [a_B^-1, a_B is the first Bohr radius]
2) q/q_F (q_F being the Fermi vector)
3) Chi(q) [finite-size corrected]
4) delta_Chi(q) [statistical error]
5) Chi(q) [uncorrected PIMC data]
6) G(q) [finite-size corrected]
7) delta_G(q) [statistical error]
8 G(q) [uncorrected PIMC data]


The files "SSF_rs_ theta_ .txt" contain data for the static structure factor with the following key:
1) q [a_B^-1]
2) S(q)
3) delta_S(q) [statistical error]
