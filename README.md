# Linear Regression
Performing **regression** of several degrees on the following data points, which were affected by **white** and **Poisson noise**. Additionally, studying its **MSE loss** and **bias-variance trade-off**.

$X = np.arange(-10,10,0.2)$

$Y = 2cos(X)/-\pi+(2x)/(2\pi)+2\times cos(3x)/(-3\pi)$

## White Noise
| Regression | Best Degree | Worst Degree |
| --- | --- | --- |
| <img src="/readme_images/WN.png"> | <img src="/readme_images/WN_best.png"> | <img src="/readme_images/WN_worst.png"> |
### Evaluation
| MSE Loss | Bias | Variance |
| --- | --- | --- |
| <img src="/readme_images/WN_mse.png"> | <img src="/readme_images/WN_bias.png"> | <img src="/readme_images/WN_variance.png"> |

## Poisson Noise
| Regression | Best Degree | Worst Degree |
| --- | --- | --- |
| <img src="/readme_images/PN.png"> | <img src="/readme_images/PN_best.png"> | <img src="/readme_images/PN_worst.png"> |
### Evaluation
| MSE Loss | Bias | Variance |
| --- | --- | --- |
| <img src="/readme_images/PN_mse.png"> | <img src="/readme_images/PN_bias.png"> | <img src="/readme_images/PN_variance.png"> |
