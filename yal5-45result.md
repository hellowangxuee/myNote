####yalmip法 VS 前向选择法

* 收敛至最优解
  * 实验收敛至最优解UE = 15 , λ=1，ρ=1
  * 目标函数能够快速收敛接近到集中式解法

![](.\img\Objective.png)

* 残差图

  ![](.\img\Residual.png)

* 设备数量对目标函数的影响

  * 参数设置：λ=1，ρ=1

![](.\img\UEObjective.png)

* 参数λ对目标函数的影响

  * 参数设置：UE=5

  ![](.\img\λObjective.png)

* 参数 ρ 对目标函数的影响

  * 参数设置：UE=5， λ=1.0

  * ![](.\img\ρObjective.png)

* 均方误差对比图

  ![](.\img\MSEError.png)

* R2图

  ![](./img/R2.png)

* R2_Adjusted图

  ![](./img/R^2Adjusted.png)

* CDF图

  * λ  ρ 参数发生变化时的iter + UE=10时，改变 ρ 值

  ![](.\img\CDF.png)