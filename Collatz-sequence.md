Collatz序列形式如下：我们从 $x_0$ 开始，我们通过下面的表达式来寻找下一个数：

$$x_{i+1}=\begin{cases}x_i/2,& 如果x_i是偶数\\
3x_i+1,& 如果x_i是奇数 \end{cases}$$

如果 $x_i=1$, 停止迭代，找到了整个序列.

例如，如果我们从 $x_0=5$ 开始，我们得到的序列是
"5, 16, 8, 4, 2, 1",
据推测，虽然没有证实，每个数字链最终会截止到1.

打印 $x_0=103$ 的Collatz序列
(提示：为使计算结果保持整数，除法可用“//”，如 $x_i$//2).

#### 注意：不要修改本文件
