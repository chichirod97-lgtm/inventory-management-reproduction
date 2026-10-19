# 端到端库存管理：复现审计与学习材料 / End-to-End Inventory Management: Replication Audit and Learning Materials

## 重要结论 / Important finding

中文：本项目已使用用户提供的作者复现包重新运行可执行的离线分析 Notebook。我们能够复算包内 3,000 个 SKU 样本上的作者分析输出；但这些结果不等于论文完整实证结果。论文报告的离线实验使用 24,333 个 SKU，字段实验的样本规模也远大于 ZIP 中每组 500 对 SKU/DC 的抽样文件。现有 ZIP 因而不足以精确复现论文全部发表表格、模型训练和实验统计量。请先阅读复现审计页。

English: We reran the executable offline-analysis notebook from the author package supplied by the user. We can recompute the authors’ analysis output on the package’s 3,000-SKU sample, but this is not the paper’s full empirical result. The paper reports an offline experiment with 24,333 SKUs, and its field experiment is much larger than the ZIP’s sampled files of 500 SKU/DC pairs per group. The supplied ZIP is therefore insufficient to reproduce every published table, model training run, and experimental statistic exactly. Read the replication audit first.

## Reports

- [复现审计：ZIP 能复现什么 / Replication audit: what the ZIP reproduces](docs/00_author_package_reproduction.html)
- [项目首页 / Project homepage](docs/index.html)
- [附录 B 合成方法练习 / Appendix B synthetic-method exercise](docs/01_appendix_b_synthetic_replication.html)
- [M5 库存策略扩展 / M5 inventory-policy extension](docs/02_m5_inventory_experiment.html)
- [模拟 DID 研究流程 / Simulated DID workflow](docs/03_simulated_did_research_workflow.html)

## 范围与数据 / Scope and data

中文：公开仓库仅包含 HTML 报告和汇总结果，不包含作者原始 CSV、源 Notebook 或可能受限的商业数据。附录 B、M5 和 DID 页面是教学练习/方法扩展，不能当作论文全文的精确复现。样本级重算与原文结果的差异及其限制见审计页。

English: The public repository contains HTML reports and aggregate results only; it does not include the authors’ raw CSV files, source notebooks, or potentially restricted business data. The Appendix B, M5, and DID pages are learning exercises or methodological extensions, not exact reproductions of the full paper. The audit page documents the sample-level calculations, differences from the article, and limitations.

Article: [Management Science DOI](https://doi.org/10.1287/mnsc.2022.4564) · [INFORMS supplementary-material page](https://pubsonline.informs.org/doi/suppl/10.1287/mnsc.2022.4564)
