# QQ-NET

This code solves the QQ optimization from input QSM and mGRE data with 8 echoes using a deep neural network (NET). 
For details see: https://pubmed.ncbi.nlm.nih.gov/34719059/

Download model, code, and data: https://wcm.box.com/s/v1thrs0ezuuhb13cdho1xaoiu3bd9h5j

To run the code, download all the files into a folder, make sure all the libraries listed in codes/basics/unet3d_b_limt_m.py exist, and run /codes/QQ_NET_test_simul.ipynb.

QQ-NET result will be saved /result/SNR100_NET_p5_trial*_overlap30.mat

To plot results in MATLAB, run /result/see_simul_horizontal.m
