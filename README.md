# PyAEDT for HFSS: ML Data Automation
**A Framework for Automated HFSS Simulation and Data Generation for Machine Learning**
<br>
**一个基于 PyAEDT 的 HFSS 自动化仿真与机器学习数据生成框架**

---

This repository provides scripts to automate Ansys HFSS simulations using PyAEDT, aimed at generating large datasets for machine learning applications like surrogate modeling and optimization.

本仓库提供通过 PyAEDT 实现 Ansys HFSS 自动化的脚本，旨在为机器学习应用（如代理建模、优化等）生成大规模数据集。

## 核心特性 | Features

-   **Parametric Modeling**: Programmatically create complex 3D models.
-   **Automated Workflow**: Automatically assign materials, boundaries, and excitations.
-   **Batch Simulation**: Configure and run multiple simulations without manual intervention.
-   **Data Extraction**: Extract and save results like S-parameters for analysis.

---
-   **参数化建模**: 以编程方式创建复杂三维模型。
-   **自动化工作流**: 自动分配材料、边界和激励。
-   **批量化仿真**: 无需手动干预，批量配置并运行仿真。
-   **数据提取**: 提取并保存S参数等结果用于后续分析。

## 环境要求 | Requirements

-   **Ansys Electronics Desktop**: `2025 R2` or later
-   **Python**: `3.10+`
-   **PyAEDT**: `pip install ansys-aedt-core`

## 快速开始 | Getting Started

1.  Clone this repository.
2.  Install the required Python libraries.
3.  Open and run the `antenna-test.ipynb` Jupyter Notebook to see a full end-to-end example.

---
1.  克隆本仓库。
2.  安装所需的 Python 库。
3.  打开并运行 `antenna-test.ipynb` Jupyter Notebook 查看完整的端到端示例。


## 示例解析: `antenna-test.ipynb` | Example Walkthrough

The `antenna-test.ipynb` notebook demonstrates a complete process for a patch antenna: from programmatic CAD creation and boundary setup to running the simulation and plotting the S11 results. It serves as an excellent starting point and reference for your own automation scripts.

`antenna-test.ipynb` 文件演示了针对一个微带贴片天线的完整流程：从程序化CAD建模、边界条件设置，到最终运行仿真并绘制S11结果。它可以作为您编写自己自动化脚本的绝佳起点和参考。

## 贡献 | Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

欢迎任何形式的贡献！请随时创建 Issue 或提交 Pull Request。

## 授权 | License

This project is licensed under the MIT License.

本项目基于 MIT 许可证开源。