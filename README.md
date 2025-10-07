# 📚 Python-for-DataAnalysis-Projects：学习代码笔记

这是一个用于记录个人学习**《利用 Python 进行数据分析》**一书的代码笔记仓库。所有 Jupyter Notebook 文件旨在复现书中的关键概念、代码示例，并进行扩展练习，以便深入理解数据清洗、数据转换和数据分析的核心技术。

---

## 📖 原著信息

本仓库基于以下图书的学习和实践：

| 属性 | 内容 |
| :--- | :--- |
| **书名** | 利用 Python 进行数据分析（原书第 3 版） |
| **原作名** | Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter |
| **作者** | Wes McKinney (pandas 库的创始人) |
| **译者** | 陈松 |
| **出版年** | 2023-10 |
| **ISBN** | 9787111726722 |
| **页数/定价** | 502页 / 149.00元 |

---

## 🧭 仓库目录与核心内容

本仓库的 Notebook 文件将按照原书的章节结构进行组织和命名，以方便查找。项目重点涵盖了 **NumPy** 和 **pandas** 两个 Python 核心库的深入应用。

### 第一部分：Python 基础、Jupyter 与 NumPy

| 章节 | 核心主题 | 学习笔记内容 |
| :--- | :--- | :--- |
| **第 2 章** | Python 语言基础 | 基础数据结构、控制流、函数、文件操作等。 |
| **第 3 章** | $\text{NumPy}$ 基础 | $\text{ndarray}$ 的创建、切片与索引、通用函数 (ufunc)、线性代数。 |

### 第二部分：pandas 的数据整理与分析

| 章节 | 核心主题 | 学习笔记内容 |
| :--- | :--- | :--- |
| **第 5 章** | $\text{pandas}$ 入门 | $\text{Series}$ 与 $\text{DataFrame}$ 数据结构、索引、轴、基本功能。 |
| **第 6 章** | 数据加载、存储与文件格式 | 读取 $\text{CSV}$、$\text{Excel}$、$\text{JSON}$、$\text{HTML}$ 等数据源。 |
| **第 7 章** | 数据清洗与准备 | 缺失值处理 ($\text{fillna}$)、数据转换、字符串操作、离散化。 |
| **第 8 章** | 数据规整：聚合、合并与重塑 | 层次化索引、数据合并 ($\text{merge}$)、重塑 ($\text{pivot}$)。 |
| **第 9 章** | 绘图与可视化 | 使用 $\text{matplotlib}$ 和 $\text{pandas}$ 内置函数进行数据探索性可视化。 |
| **第 10 章** | 数据聚合与分组操作 | $\text{Groupby}$ 机制、聚合函数、跨期和时间序列操作。 |

### 第三部分：高级主题（时间序列与高级 NumPy）

| 章节 | 核心主题 | 学习笔记内容 |
| :--- | :--- | :--- |
| **第 11 章** | 时间序列 | 时间日期数据类型、频率转换、重采样、移动窗口函数。 |
| **第 12 章** | 建模工具介绍 | 深入 $\text{NumPy}$ 高级应用、性能优化等。 |

---

## ✨ 如何运行代码？

本仓库中的 $\text{.ipynb}$ 文件推荐在 **Jupyter Notebook** 或 **VS Code** 环境中运行。

1.  **克隆仓库：**
    ```bash
    git clone git@github.com:novak-zhc/Python-for-DataAnalysis-Projects.git
    ```
2.  **创建 Conda 环境：**
    推荐使用 $\text{Anaconda}$ 或 $\text{Miniconda}$ 创建隔离环境，并安装 `pandas`, `numpy`, `jupyter` 等核心依赖。
3.  **启动环境：**
    ```bash
    conda activate <环境名>
    ```
4.  **打开 Notebook：**
    在 VS Code 中直接打开 $\text{.ipynb}$ 文件，或在终端中运行 `jupyter notebook`。

欢迎查阅和交流！
