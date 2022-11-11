# Finance-Portfolio

# US500

## Preprocessing

### 1. drop the nan data 
First, Trial is the removing the data of nan for the objective of baseline.
![original](https://user-images.githubusercontent.com/117700793/201296489-6a1801d8-ee9d-45cc-a6d5-70d8d5d94e4d.png)

This graph is the original Graph of US500 and we can recognize the fact that US500 has some kind of trend.

![log_USD](https://user-images.githubusercontent.com/117700793/201296790-64e1a257-baa7-49bb-a674-29fc66a06d49.png)

This graph is the graph of US500 taking log function. And this process has the objective of smoothing the US500's movement.

![norm_US500](https://user-images.githubusercontent.com/117700793/201297576-d4841db4-b601-4558-a5a2-04e94385a7fb.png)

This graph is the graph of US500 taking the standard normalization. This process has the objective of unifying the unit of other Financial Commodities.

![First_log_and_Norm](https://user-images.githubusercontent.com/117700793/201298569-f07f44f3-d7af-4162-bdfa-a57bbcbfa62c.png)

This graph is the graph of US500 , at first taking the log function and then taking the standard normalization process, of the objective of , first, making the US500's movement smoothing and then taking unifying the other financial commodities's unit.
