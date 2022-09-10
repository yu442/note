## Static Program Analysis
(静态程序分析)
## Pointer Analysis-Context Sensitivity
### Compare Sensitive with Insensitive
![](1.png)
![](2.png)
### Contents
![](3.png)
#### Introduction
![](4.png)
*Imprecision of Context Sensitive*
![](5.png)
*Clone实现上下文敏感*
![](6.png)
*堆上下文敏感*
![](7.png)
*没有使用堆上下文敏感*
![](8.png)
*使用堆上下文敏感*
#### Context Sensitive Pointer Analysis:Rules
![](9.png)
*Domains and Notations* 
![](10.png)*Assign*
![](11.png)*Store*
![](12.png)*Load*
![](13.png)*Rules*
![](14.png)*Call*
![](15.png)*Example*

Conclusion:上下文不敏感就像你进入一个小黑屋，不记得入口回去的时候可能会走多个入口；上下文敏感就像你进入一个小黑屋，但是记得入口回去的时候走的是来时的入入口，所以会更准确。

#### Context Sensitive Pointer Analysis : Algorithm
![](16.png)
![](17.png)
#### Context Sensitivity variants
Context Insensitivity 是CS的一个特例，select为空
![](18.png)
##### Call-Site Sensitivity
![](19.png)
![](20.png)
![](21.png)
![](22.png)
##### Object Sensitivity
![](23.png) 
Compare Call-Site with Object Sensitivity
![](24.png)
![](25.png)
![](26.png)
![](27.png)
##### Type Sensitivity
![](28.png)
![](29.png)
![](30.png)
*三者时间和效率对比* 
![](31.png)
