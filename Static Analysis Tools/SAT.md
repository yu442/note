# Static Analysis Tools
## Klocwork(Perforce)
```dos
在静态代码分析领域，Klocwork 算得上是领头羊，这可能也与其专攻大型代码库的
优势相关。Klocwork 有 1000 多个检查器，对症不同种类代码缺陷，同时用户可
定制检查方案。此外，假正例（false positives）与假负例（false negatives）
等代码缺陷筛查也是其优势功能（很多工具目前无法做到）。除此之外，Klocwork 
可提供差异分析，这个功能并不常见。因此，用户可以大幅节省新代码或修改代码的
分析时间。Klocwork 不仅是一个静态代码分析工具，同时也是一个 SAST（静态应
用程序安全测试工具），几乎全面覆盖了安全性能方面。此外，它还集成了许多 
IDE 和 CI/CD 工具。最关键的是，Klocwork 还与 Incredbuild 深度集成，全
马力加速代码分析。
```
## Cppcheck
```dos
Cppcheck 是另一个热门的静态代码分析工具，集开源、免费、跨平台且专用于C 和 
C++ 的优势于一身。Cppcheck 最大的特点是易用性，操作简单为它吸引了一大批用
户。使用 Cppcheck 时，用户无需做任何调整或修改，这也是初学者爱用 
Cppcheck 的主要原因。另外，Cppcheck 的假正率（false positives）较低，
这也是这个工具的另一优势。
```

## CppDepend(CoderGears)
```dos
CppDepend 是一个商业的 C++ 静态代码分析工具。有别于其他工具，CppDepend 
专注于分析而不是纠错，同时搭建可视化代码库体系结构（例如，正确分层、依赖关
系），因此经常作为其他静态代码分析工具的补充。CppDepend 的依赖关系图、趋势
监控（监控构建变化）都是很值得深入研究的独特功能。与 Klocwork 一样，
CppDepend 也支持用户自定义规则。
```
## Parasoft C/C++test
```dos
Parasoft C/C++test 是流行的 C/C++ 商业测试工具，其中包括静态代码分析工
具。Parasoft C/C++test 主要面向企业和嵌入式应用程序（出于安全原因，这些行
业通常需要获得静态代码分析工具），以及动态代码分析、单元测试、代码覆盖、运行
时分析等功能。在静态代码分析方面，Parasoft 工具的独特之处在其丰富的技术和规
则，数量高达 2500 条。此外，Parasoft 还提供认证套件（Qualification 
Kit）和功能安全认证。不过，Parasoft 真正的价值在于全面性，其代码分析、检测
功覆盖了整个周期，包括：分析代码、确定结果优先级和管理结果（包括将结果分配给
团队成员）。最近，Parasoft 宣布支持 IAR Systems 针对 Linux for Arm 的
构建工具，该工具可帮助开发人员在 Linux 服务器上配置快速、可扩展的 CI/CD 管
道。
```
## PVS Studio
```dos
顶级静态代码分析工具榜单，PVS Studio 必须榜上有名。PVS Studio 作为一个商
业工具，专长是深度检测，挖掘一般注意不到的隐藏 bug，如打字错误、复制粘贴错
误。此外，PVS Studio 还与流行的 CI 工具集成，如 Jenkins、TeamCity、
Azure DevOps 等。SonarQube 也在其集成列表之内，SonarQube 是一种与静态
代码分析工具很类似工具，但它更偏向于检测代码方面。PVS Studio 的另一个独特
优势在于其文档内容，包含了超过 700 页的海量信息。
```
## Coverity(Synopsys)
```dos
Coverity 静态分析名气不小。Coverity 主要用于在编写代码时查找错误和弱点，
为开发者节省时间，也避免了后续的麻烦。此外，Coverity 还有提供了一个免费的云
服务，Coverity Scan，主要针对开源社区。这个功能以准确性、全面性著称，其代
码分析较同类工具更为深入，检查器的开发也建立在对 100 多亿行代码的深入分析基
础上。
```

## Polyspace(MathWorks)
```dos
Polyspace 是一个静态分析工具，可识别、修复或挖掘潜在的运行时错误（如：除以零），
并检查源代码是否遵循 MISRA C、MISRA C++ 和 JSF++ 等代码标准。此外，
Polyspace 还可以将必须手动审查的未经验证代码突出显示。其广泛用于嵌入式软件
领域，尤其是安全性能至上的交通运输领域，如汽车、航空航天和铁路运输领域。
```

## Flawfinder
```dos
Flawfinder 是由安全专家 David A. Wheeler 开发的免费开源工具。正如其品牌
名称代表的含义，Flawfinder 专注定位安全缺陷，并按风险级别排序（风险最高者
排在第一位）。Flawfinder 使用直接、简单和快速，备受初学者喜爱。
```

## Helix QAC(Perforce)
```dos
Helix QAC 是 Perforce 针对 C 、C++ 开发的另一个出色的代码分析工具，在
“严格管制和安全至上行业”中很受欢迎，例如汽车行业。Helix QAC 自动强制执行编
码标准，如 MISRA®，以确保代码符合要求
```