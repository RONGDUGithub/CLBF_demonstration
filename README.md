# BLF_demonstration

This is the MATLAB code and dataset corresponding to our paper. To run the program, click on the files demo.m or demo_sampling.m.

The program's output consists of two matrices: mean_result, which represents the evaluation of the means, and distribution_result, which represents the cosine distance between the estimated stream and the original stream. 

For demo.m, each row corresponds to the results for different epsilon values, ranging from 0.5 to 3. Each column represents a different scheme, in the following order: naive, 1LB, FLB, CFLB, and ToPL.

For demo_sampling.m, the columns represent the following schemes: naive, sampling, FLB, CFLB, FLB-S, and CFLB-S.
