# prediction of vitamin C concentration vol.2

Improved version of neural network in the study of influence of an image color standarizaion on the quality of a regression model constructed using neural networks. The increase of R2 value and MSE was noted for the achieved results in comparison to the previous version.

The final architecture is introduced in the file: example_of_final_net.ipynb

# prediction of vitamin C concentration vol.1

Influence of an image color standarizaion on the quality of a regression model constructed using neural networks. A color conversion based on histogram matching is proposed. A custom color chart was presented based on an initial series of studies and digital imaging. Photos of a solutions were made under two different light conditions (natural and artificial lightning). The mean squared error for the test set ranged between 2.92  and 7.96 for the concentration range of vitamin C from 0 to 87.72 µg/mL, in comparison, the non-standardized variant was at the level of 15.61-34.13 µg/mL. The R2 reached approximately 0.99 for each of the standardized variants. This methods allows removal of light reflections on the shiny surface of solutions, which is quite a common problem in liquid samples.
