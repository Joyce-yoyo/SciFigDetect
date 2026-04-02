# SciFigDetect

SciFigDetect 的 GitHub 仓库主页模板，适合像 [MDPE](https://github.com/cai-cong/MDPE) 那样把数据集概览、下载方式、基线结果和引用方式集中展示。

## Homepage

这个仓库已经包含一个可直接用于 GitHub Pages 的静态页面：

- `index.html`
- `styles.css`
- `script.js`

启用 GitHub Pages 后，可以将 `main` 分支根目录直接发布为数据集主页。

## What To Replace

请优先替换下面这些占位内容：

- `[DATASET_LINK]`
- `[PAPER_LINK]`
- `[License Name]`
- 联系邮箱
- BibTeX
- Benchmark 表格中的模型和分数

## Recommended Sections

建议在页面中保留这些部分：

- 数据集简介
- 关键特性
- 数据结构
- 下载与使用
- 基线结果
- 引用

## Deploy To GitHub Pages

1. 把仓库推送到 GitHub。
2. 打开仓库 `Settings > Pages`。
3. 选择从当前分支部署。
4. 分支选择默认分支，目录选择 `/ (root)`。

## Citation

```bibtex
@inproceedings{scifigdetect2026,
  title={SciFigDetect: A Dataset for Scientific Figure Detection},
  author={Author One and Author Two and Author Three},
  booktitle={Conference or Journal},
  year={2026}
}
```
