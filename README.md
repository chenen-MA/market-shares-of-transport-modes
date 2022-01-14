# market-shares-of-transport-modes
this project is about how to predict the market share of transport modes. you can check the details in my paper. the project includes the original data I collected and the python code of how I operated it. the methods include K-MEANS, CPA, Elastic-Network, SVR, and GPR.

in the zip file (github data), there are 11 excels.
0_raw_relative_variables_for_program: is the original data from world bank dataset. it is used to do kmeans.
1_catagories: is the kmeans result, which will be used to do PCA
2_0_PCA_result: is the PCA result. this will be used to do the independent variable prediction.
2_1_IV_pred: is the prediction results using elastic network, SVR and GPR and the combination results.

3_shares_calc_original: is the original data of medium dataset and small dataset, which are from China statistical bureau.
4_interpolate_dataset: is the result after interpolation, which will be used in the following prediction.

5_1_small_dataset_results: is the prediciton result using SVR method
5_medium_dataset_results: the predicition result using Elastic network
6_1_small_dataset_operation and 6_medium_dataset_operation: because the predcition result is not the market share (which was design and illustrated in the paper), I need to convert these prediction results to the market share values.

7_endowment_operation: is the operation process of how to get the efficiency improvement rate and the change rates of transportation modes, which will be used directly in the CGE model.
