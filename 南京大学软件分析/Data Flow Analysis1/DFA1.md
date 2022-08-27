## Static Program Analysis
(静态程序分析)
### Data Flow Analysis
#### contents
![](1.png)
##### Data Flow Analysis 
    1. over-approximation改为safe-approximation
    2. may analysis:over
    3. must analysis:under
##### Preliminaries of Data Flow Analysis 
![](2.png)
*控制流约束的概念*
##### Data Flow Analysis Applications
![](3.png)
*三个例子应用*
###### （1）Reaching Definitions Analysis 
![](5.png)
![](4.png)
*what is Reaching Definitions Analysis* 
![](6.png)
*Understand Reaching Definitions->采用字节码*
![](7.png)
**Algorithm*
![](8.png)
*Example*
###### （2）Live Variables Analysis 
![](9.png)
*what is Live Variables Analysis* 
![](10.png)
*Understand Live Variables Analysis* 
![](11.png)
**Algorithm*
![](12.png)
*Example*
###### （3）Available Expressions Analysis 
![](13.png)
*what is Available Expressions Analysis* 
![](14.png)
*Understand Available Expressions Analysis* 
![](15.png)
**Algorithm*
![](16.png)
###### Analysis Comparison
![](17.png)
