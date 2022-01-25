## 混淆电路

### 一. 混淆电路的发展现状

1982 年：姚期智提出混淆电路，此时的混淆电路识两方计算

2009 年：Lindell 等给出了安全性证明和详细介绍

2013 年：Goldwasser 给出了简化形式

### 二. 逻辑电路

### 三. 混淆电路

### 三.GMW 协议

### 四.BGW 协议


### 五.总结

经过近几年的发展，MPC协议系统已经不再使用严格的电路表示，而是使用混合模型，在混合模型中，函数被编译成一组优化的子协议函数，用于公共操作。这组原语可以包括传统的基于电路的协议模型，可以在单个协议中被无缝地描述。混合模型系统通常将中间值表示为一个大的有限域上的密钥分享。它们可以使用信息论和密码协议的混合，因此，计算参与方的数量和威胁模型都不同。

与严格的基于电路的模型相比，混合模型允许存在非常不同的性能特性。例如，在有限域中，比较、位移和相等性测试等操作作为算术电路表示代价高昂。然而，操作密钥分享的专用子协议在共享计算结果方面却非常高效。