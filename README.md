# Determining-the-merging-capability-of-Wide-and-Deep-Network-and-Long-term-Recurrent-Convolutional-Network

The goal of this project is to understandWide and Deep Neural Network WDNN [1]
and Long-short Recurrent Convolutional Network [2]. Based on these two models,
a new model LRCN_WDNN is created by merging and tested on SNP-based and
gene burden-based data. Since the LRCN_WDNN model is complex, Bayesian
optimization is performed to approximate the best set of parameters. The results
show that LRCN_WDNN improved model is able to achieve training accuracy of
96.52% and validation accuracy of 85.63% which is higher than LRCN. Though the
accuracy is higher, the model is overfitted. To overcome this, dropout rates, kernel
size, filters are increased and the number of units in dense layers are decreased in
descending order. The final training accuracy was 84% and validation accuracy
was 82% a significant decrease in accuracy. This project shows, LRCN_WDNN
model is able to learn equivalent to LRCN.
