# sm3_birthday_attack
生日问题的取值范围是在一年的365天之内，也就是说生日只可能有365种可能性。

我们将这个问题扩展一下到一般的情况，假设有一个函数f，它的输出范围是H，那么我们的攻击就是找到两个不同的x，y，让f(x)=f(y)。

这时候，我们可以称x和y发生了碰撞。

根据概率论的公式，我们想要达到50%的几率，那么需要尝试的次数是:x^(1/2)
