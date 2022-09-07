## Static Program Analysis
(静态程序分析)
## Pointer Analysis-Foundation
### Contents
![](1.png)
#### Rules
![](2.png)
*New*
![](3.png)
*Assign*
![](4.png)
*Store*
![](5.png)
*Load*
#### How to implement Pointer Analysis
![](6.png)
![](7.png)
![](8.png)
*With PFG,pointer analysis can be solved by computing transitive closure of the PFG*
![](9.png)
#### Pointer Analysis:Algorithms
##### Handling of New and Assign
![](10.png)
![](11.png)
![](12.png)
*Avoid Redundancy*
##### Handling of Store and Load
![](13.png)
##### Review
![](14.png)
##### Example
![](15.png)
#### Pointer Analysis with Method Calls
![](16.png)
*Comparison with CFA* 
![](18.png)
*Four Steps*
![](17.png)
![](19.png)
*Inter procedural Pointer Analysis* 
![](20.png)
*Algorithm*
![](21.png)
Why do we need to determine whether an edge exists?
决定是否连接边的是oi的类型，之前可能传递过相同类型的对象，L可能会处理多次

