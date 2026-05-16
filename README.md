# SDM-Phacking
sPselect是一个用于空间计量模型（Spatial Econometric Model）的控制变量组合自动筛选工具。   基于 `tuples`、`foreach` 循环与 `wordcount` 等基础命令，穷举所有控制变量组合， 自动识别同时满足以下统计显著性条件的变量组合：  - ✅ 核心解释变量 p 值（`pvalue_X`） - ✅ 空间滞后解释变量 p 值（`pvalue_WX`） - ✅ 空间自相关系数 ρ（`rho`） - ✅ 直接效应 / 间接效应 / 总效应显著性
