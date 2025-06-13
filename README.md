# 量子力学II课程论文（2025春季）

本项目是复旦大学2025年春季学期《量子力学II》课程**APT组**的期末课题，旨在研究、推导并验证**高阶绝热微扰理论**。

## 项目内容与结构

本仓库包含课程论文所涉及数值算例的代码与源数据：

```
.
├── standard_approach.ipynb    # 标准绝热修正方法
├── Berry-Iteration-Test/      # Berry迭代法
└── dapt_reproduction/         # 简并绝热微扰理论(DAPT)
```

1. **标准绝热修正方法 (`standard_approach.ipynb`)**
   - 使用文献[2]中关于APT的二能级模型，通过数值实验展示传统“标准方法”的理论缺陷与收敛性问题。

2. **Berry迭代法 (`Berry-Iteration-Test/`)**
   - 使用文献[2]中关于APT的二能级模型，数值测试Berry迭代法的有效性及其渐近收敛的特性。这是一个独立的Git子模块，详情请见其内部的`README.md`。

3. **简并绝热微扰理论(DAPT)复现 (`dapt_reproduction/`)**
   - 复现文献[3]中关于DAPT的四能级模型算例，以验证其理论框架。这是一个独立的Git子模块，详情请见其内部的`README.md`。

## 核心参考文献

1. M. V. Berry, "Quantum phase corrections from adiabatic iteration," *Proc. R. Soc. Lond. A* **414**, 31 (1987). [DOI: 10.1098/rspa.1987.0131](https://doi.org/10.1098/rspa.1987.0131)
2. G. Rigolin, G. Ortiz, and V. H. Ponce, "Beyond the Quantum Adiabatic Approximation: Adiabatic Perturbation Theory," *Phys. Rev. A* **78**, 052508 (2008). [DOI: 10.1103/PhysRevA.78.052508](https://doi.org/10.1103/PhysRevA.78.052508)
3. G. Rigolin and G. Ortiz, "Degenerate Adiabatic Perturbation Theory: Foundations and Applications," *Phys. Rev. A* **90**, 022104 (2014). [DOI: 10.1103/PhysRevA.90.022104](https://doi.org/10.1103/PhysRevA.90.022104)

## 小组成员

张世范、谢昀城、莫双铭、黄海洋、杨远青
